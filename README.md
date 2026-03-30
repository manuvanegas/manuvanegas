### Hi there 👋
 
I'm a geospatial data engineer and scientific modeler working at the intersection of spatial data infrastructure and computational environmental science.
 
My current work involves building end-to-end geospatial pipelines and analysis systems — from production APIs serving raster data over cloud storage to HPC-scale climate model processing and process-based ecological simulation. I work primarily in Python, with Julia and R for modeling and research tasks.
 
**What I build:**
- Geospatial data pipelines: COG/GeoTIFF, NetCDF, STAC catalogs, AWS S3, rasterio, GDAL, xarray
- Async geospatial APIs: FastAPI, TiTiler, windowed raster reads at scale
- HPC workflows: SLURM array jobs, Dask, parallelized simulation pipelines
- Process-based ecological models: spatially explicit IBMs, Approximate Bayesian Computation, genetic algorithm optimization
 
**Selected projects:**
 
🌍 **SKoPE Geospatial Platform** — Contributing to a production paleoclimate data system: built a Python/GDAL pipeline converting multi-band GeoTIFFs into Cloud Optimized GeoTIFFs with a STAC catalog and temporally-indexed lookup table on AWS S3, designed an async geospatial analysis API (FastAPI + rasterio) for windowed reads and zonal statistics at scale, and led integration of a TiTiler tile-serving microservice across the full stack. [[skope-api](https://github.com/manuvanegas/skope-api)] [[skope-datasets](https://github.com/manuvanegas/skope-datasets)] [[skopeui](https://github.com/manuvanegas/skopeui)]
 
🌡️ **SDM4CI Climate Intervention Analysis** — Multi-stage geospatial pipeline processing CESM2-WACCM climate model output across 7 scenarios and 35 years, with a Bayesian actor decision model designed as a component of a coupled human-Earth system model. Python, xarray, xesmf, SLURM, Dask, Bokeh.
 
🌱 **SpatialRust** — Spatially explicit, process-based model of coffee agroforestry systems, coupling shade tree dynamics, plant physiology, and pathogen dispersal. Calibrated using Approximate Bayesian Computation at 1-million-simulation scale; management strategies optimized with a genetic algorithm. Julia, SLURM. [[Zenodo](https://doi.org/10.5281/zenodo.8237935)] [[Repo](https://github.com/manuvanegas/SpatialRustModel)]
 
📦 **Containerization for computational models** — Tutorials and tools supporting reproducible deployment of scientific models across HPC and cloud environments. Docker, Apptainer. [[Article](https://doi.org/10.18174/sesmo.18074)]
 
