### Hi there 👋
I build software for geospatial, climate, and environmental data, from data pipelines and APIs to map interfaces. I am a scientist by training (PhD in Biological Design), and I work mostly in Python and TypeScript, with Julia and R for modeling.

**What I build**

- Full stack web applications: Django REST Framework, FastAPI, PostgreSQL, Redis, Angular, Vue/Nuxt
- Raster and map services: async analysis APIs, windowed reads and zonal statistics, TiTiler, MapLibre GL JS
- Geospatial data pipelines: COG, STAC, GeoParquet, NetCDF, rasterio, GDAL, GeoPandas, PostGIS, xarray, xESMF
- Scientific computing: SLURM, Dask, process-based simulation, Bayesian calibration, statistical verification
- LLM extraction systems: hybrid retrieval, structured output, source-grounded answers, evaluation

**Selected projects**

🌍 **SKoPE Geospatial Platform:** Led the modernization of an open paleoclimate data platform across the full stack: an async FastAPI and rasterio analysis API, a dataset ingestion pipeline that publishes multi-band rasters as immutable, versioned releases of Cloud Optimized GeoTIFFs with STAC metadata, a TiTiler tile service, and a Nuxt and MapLibre interface. A separate harness recomputed the API's results from the source rasters across 1,440 analysis cases, and discrepancies were fixed until every case matched. Benchmarking 48 COG encoding configurations cut full-range time series extraction by about 60% from the previous encoding on an archive of 1,898 annual timesteps. [[skope-api](https://github.com/manuvanegas/skope-api/tree/dataset-releases)] [[skopeui](https://github.com/manuvanegas/skopeui/tree/dataset-releases)] [[skope-datasets](https://github.com/manuvanegas/skope-datasets)]

🌳 **Piedemonte Forest Loss:** Independent analysis of forest clearing in Colombia's Andean-Amazon piedmont before and after the 2014 ceasefire. Maps annual forest loss from 30 m MapBiomas land cover with a persistence rule, separates old-growth from secondary forest, delineates 2.2 million loss patches stored as GeoParquet, and measures each one in PostGIS against roads, rivers, protected areas, Indigenous territories, and earlier clearings. Subdividing the largest polygons made nearest-neighbor queries about 180x faster with identical results. Python, PostGIS, GeoPandas, rasterio, Docker Compose, Make. [[Repo](https://github.com/manuvanegas/piedemonte-forest)]

🧬 **Arizona Pathogen Genomics Analytics Platform:** Full stack feature development on a production platform used by researchers at a state health department and three universities. Built a catalog overview page with linked charts backed by server-side aggregates, along with data explorer presets and notification features. Django REST Framework, PostgreSQL, Angular, NgRx.

🌡️ **SDM4CI Climate Intervention Analysis:** Multi-stage HPC pipeline over CESM2-WACCM climate model output across 7 scenarios: regrids daily global fields, masks regions, and computes population-weighted heat stress indices from two physiology-based metrics. Python, xarray, xESMF, Dask, SLURM, Bokeh.

📄 **Carbon Accounting Standards Extraction:** Pipeline that answers a structured questionnaire for a corpus of 200+ carbon accounting standards with open-weights models. Combines section-level routing, hybrid retrieval (FAISS, BM25, cross-encoder reranking), and enforced answer schemas, and makes its answers traceable to verified passages in the source documents. Python, Docling, Instructor, Pydantic.

🔄 **CoMSES Model Porting Verification:** Statistical quality gate for a system that uses LLM coding agents to translate simulation models between programming languages. Tests whether a ported model behaves equivalently to the original, using PCA and Maximum Mean Discrepancy as the global gate, with MANOVA and corrected per-timestep tests to locate differences. The output shown to the porting agent is stripped of test internals so that the agent cannot game the verifier. Python, SciPy, statsmodels, Pydantic, pytest.

🌱 **SpatialRust:** Process-based, spatially explicit stochastic simulation of coffee agroforestry farms, coupling shade tree dynamics, plant physiology, and pathogen dispersal to study how management and farm layout shape disease and revenue. Calibrated with Approximate Bayesian Computation over one million parameter sets on HPC, and optimized with a custom parallel genetic algorithm. Julia, SLURM. [[Zenodo](https://doi.org/10.5281/zenodo.8237935)] [[Main model repo](https://github.com/manuvanegas/SpatialRustModel)]

**Writing**

📦 **Containerization for creating reusable agent-based models:** First-author, peer-reviewed methods article introducing Docker and containerization practices to the socio-environmental systems modeling community, with tutorial materials and GitHub Classroom workflows. [[Article](https://doi.org/10.18174/sesmo.18074)]
