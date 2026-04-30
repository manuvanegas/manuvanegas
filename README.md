### Hi there 👋
I'm a research software engineer working at the intersection of spatial data infrastructure and computational environmental science. I work primarily in Python, with Julia and R for modeling and research tasks.

**What I build:**

- Geospatial data pipelines: COG/GeoTIFF, NetCDF, STAC catalogs, AWS S3, rasterio, GDAL, xarray
- Async geospatial APIs: FastAPI, TiTiler, windowed raster reads at scale
- HPC workflows: SLURM array jobs, Dask, parallelized simulation pipelines
- Process-based ecological models: spatially explicit IBMs, Approximate Bayesian Computation, genetic algorithm optimization

**Research background (Process-based ecological models):** 

- Coupled human and natural systems across domains: agroforestry, urban water governance, and geopolitical response to climate intervention
- Parameter estimation and optimization: Approximate Bayesian Computation, genetic algorithms
- Climate model analysis: ESM output processing, spatiotemporal aggregation, scenario comparison

**Selected projects:**

🌍 **SKoPE Geospatial Platform:** Led modernization of a production paleoclimate data system: rebuilt a Python/GDAL pipeline converting multi-band GeoTIFFs into Cloud Optimized GeoTIFFs with a STAC catalog and temporally-indexed lookup table on AWS S3, redesigned an async geospatial analysis API (FastAPI + rasterio) for windowed reads and zonal statistics at scale, and led integration of a TiTiler tile-serving microservice across the full stack. [[skope-api](https://github.com/manuvanegas/skope-api)] [[skope-datasets](https://github.com/manuvanegas/skope-datasets)] [[skopeui](https://github.com/manuvanegas/skopeui)]

🌡️ **SDM4CI Climate Intervention Analysis:** Multi-stage geospatial pipeline processing CESM2-WACCM climate model output across 7 scenarios and 35 years, extending a non-geospatial heat stress model to produce raster outputs across global population grids. Python, xarray, xesmf, SLURM, Dask, Bokeh.

🌱 **SpatialRust:** Spatially explicit, process-based model of coffee agroforestry systems, coupling shade tree dynamics, plant physiology, and pathogen dispersal. Calibrated using Approximate Bayesian Computation at 1-million-simulation scale. Julia, SLURM. [[Zenodo](https://doi.org/10.5281/zenodo.8237935)] [[Main model repo](https://github.com/manuvanegas/SpatialRustModel)]

**Writing:**

📦 **Containerization for Computational Models** Peer-reviewed methods article introducing Docker and containerization practices to the socio-environmental systems modeling community, accompanied by tutorial materials and GitHub Classroom workflows for researchers learning to containerize their own models. [[Article](https://doi.org/10.18174/sesmo.18074)]
 
