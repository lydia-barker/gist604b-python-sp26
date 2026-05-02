# GIST 604B – Python for GIS

**Student:** Lydia Barker
**Course:** GIST 604B – Open Source GIS
**Module:** Module 3 - Python GIS and Containerization
**University of Arizona**

## Project Description
The workflow for this repository included following guided notebooks in which I worked with tabular, vector, and raster GIS datasets using Python. In this project, I implemented functions for Pandas and Geopandas and verified implementation by running tests through the codespace terminal.

## Tools and Technologies
- Pandas
- Geopandas
- Rasterio Library

## What I Did
- Loaded tabular data using Pandas and vector data using Geopandas
- Analyzed, ran, and tested functions to ensure proper extraction and operations of data
- Loaded raster data using a Rasterio Library, implemented functions to filter the data, and implemented functions to visualize targeted data.

## How to View / Run
- Fork the repository and open it in a GitHub Codespace
- Output of implemented functions can be found by reviewing each notebook

## Repository Structure

```
/
├── notebooks/
│   ├── pandas/
│   │   ├── 01_load_and_explore_data.ipynb
│   │   ├── 02_filter_environmental_data.ipynb
│   │   ├── 03_calculate_station_statistics.ipynb
│   │   └── 04_join_station_data.ipynb
│   ├── geopandas/
│   │   ├── 01_load_spatial_data.ipynb
│   │   ├── 02_explore_geometries.ipynb
│   │   ├── 03_coordinate_systems.ipynb
│   │   ├── 04_function_geometry_operations.ipynb
│   │   ├── 05_function_spatial_relationships.ipynb
│   │   ├── 06_function_spatial_joins.ipynb
│   │   └── 07_function_overlay_and_visualize.ipynb
│   └── rasterio/
│       └── remote_sensing_workflow.ipynb
├── src/
│   ├── pandas_basics.py
│   ├── geopandas_basics.py
│   └── download_real_data.py
├── tests/
│   ├── test_pandas_basics.py
│   ├── test_geopandas_basics.py
├── data/
│   ├── cities/
│   │   └── ne_cities_us.geojson
│   ├── ecoregions/
│   │   └── epa_level3_western_us.geojson
│   ├── protected_areas/
│   │   └── national_parks_major.geojson
│   ├── neighborhood_samples.geojson
│   ├── temperature_readings.csv
│   └── weather_stations.csv
├── .devcontainer
│   ├── devcontainer.json
│   └── DockerFile
├── .gitignore
├── pyproject.toml
├── uv.lock
└── README.md
```

## Notes

- Notebooks are for exploration and learning.
- Final implementations are in `src/`.
- Tests validate pandas and GeoPandas functionality.
- Rasterio work is completed entirely in the notebook.
