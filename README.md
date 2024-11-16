# Community-GIS-mapping
## Overview
This repository contains the code, data, and methodology for mapping health-related facilities in three urban informal settlements in Dhaka City: Kallayanpur, Dholpur, and Shyampur. The project uses interactive maps to visualize and communicate data about these settlements, including health care facilities, water collection points, sanitation, and more. Interactive maps, created using the R programming language, are used to make findings accessible and user-friendly. The repository demonstrates the potential of geocomputation to describe and change urban landscapes through data visualization.

## Project Structure
mapping-dhaka-facilities/
├── data/                      # Input data files
│   ├── shyampur_slum.csv
│   ├── kallayanpur_slum.csv
│   └── dholpur_slum.csv
├── scripts/                   # R scripts for analysis and visualization
│   ├── data_preprocessing.R   # Data cleaning and preparation
│   ├── map_creation.R         # Leaflet map creation
│   └── utilities.R            # Supporting functions
├── outputs/                   # Outputs and generated maps
│   ├── kallayanpur_map.html
│   ├── dholpur_map.html
│   └── shyampur_map.html
├── LICENSE                    # License for usage
└── README.md                  # Project documentation


## Methodology

### 1. Interactive Mapping
The maps are interactive, engaging, and provide tools for data exploration:
Rationale: To visualize facilities and boundaries dynamically and effectively.
Features: Zooming, tooltips, and interactive layers.
### 2. Software Used
The project uses the R Programming Language, leveraging its robust geospatial packages:
Leaflet: For creating interactive maps.
Tidyverse: For data wrangling and visualization.
Additional Packages: htmlwidgets, jsonlite, reactable, table1, etc.
### 3. Data Workflow

#### a) Data Cleaning:
Loaded datasets for each slum from CSV files.
Renamed columns for consistency.
Filtered subsets of facilities (e.g., healthcare, water collection points, etc.).
#### b) Map Creation:
Boundaries created using convex hull functions.
Facilities mapped with markers and tooltips.
Layers added for facility categories, allowing interactive exploration.
#### c) Visualization:
Final maps were created using the leaflet package, offering multiple basemaps and detailed interactive features.


