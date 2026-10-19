# VICTOR Workflows

## What this is
This repository is a collection of computational volcanology workflows packaged as Jupyter notebooks for running and exploring models used on the VICTOR platform. It brings together topic-specific notebooks for lava flow, ash and tephra, gas dispersion, petrology, projectile behavior, and remote sensing analysis.

### Stack
- **Language(s):** Jupyter Notebook, Python
- **Framework / runtime:** JupyterLab / Jupyter Notebook
- **Notable libraries:** NumPy, pandas, matplotlib, xarray, and geospatial/scientific Python tooling used across the notebooks

## How it's organized
```text
Ash_and_Tephra/            ash, tephra, and hazard notebooks
Gas/                       gas-dispersion and plume models
Lahars_and_PDCs/           lahar / pyroclastic density current workflows
Lavaflow/                  lava flow and flow-model notebooks
Lava Benchmark/            lava benchmark workflows and comparison cases
PDC Benchmark/             PDC benchmark workflows
Petrology_and_Magma/       petrology and magma-related workflows
Projectile/                projectile / ballistic model notebooks
Remote Sensing/            SAR, thermal, plume, and geospatial analysis notebooks
src/                       helper utilities for remote sensing workflows
OpenTopo.ipynb             topographic data access workflow
get_DEM.ipynb              DEM retrieval notebook
dem_flowgo.ipynb           DEM + FLOWGO workflow
pyBET.ipynb                benchmark model / workflow notebook
pyVOLCANS.ipynb            VICTOR workflow example notebook
