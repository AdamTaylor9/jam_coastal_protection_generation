## Installation

To set up the environment, run the following command:  

```bash
conda env create -f environment.yml`
```
## Usage
Activate the Environment
```bash
conda activate coastal-protection
```


## Notebook Description

### `final_jamaica_coastal_protection_areas.ipynb`
This notebook contains all the functions required to generate flood area protections polygons and its respective coastline segment given the flood data.

## Requirements

Ensure the following files are available for the analysis:

- **`Foundation_Data.gpkg`**:
  - Should include:
    - Coastline edges 
    - Coastline nodes
    - Mask of the island of Jamaica

- **Flood Rasters**:
  - Input raster files representing flood data.
