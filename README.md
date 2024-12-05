# Visualizing Biodiversity Loss in Phoenix, AZ
Author: Carmen Hoyt

This analysis investigates the impacts of urban expansion by assessing the changes in the Biodiversity Intactness Index (BII) for Phoenix, AZ from 2017 to 2020.

## Data

Two datasets are used in this analysis:

1. Biodiversity Intactness Index (BII) Time Series:
   
In this analysis, I use the 2017 and 2020 rasters from the `io-biodiversity` collection from the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity). The collection was filtered using the following coordinates: [-112.826843, 32.974108, -111.184387, 33.863574].

Microsoft Open Source, Matt McFarland, Rob Emanuele, Dan Morris, & Tom Augspurger. (2022). microsoft/PlanetaryComputer: October 2022 (2022.10.28). Zenodo. [https://doi.org/10.5281/zenodo.7261897](https://doi.org/10.5281/zenodo.7261897)

2. Phoenix Subdivision Shapefile:
   
The Phoenix subdivision shapefile was downloaded from the [2020 TIGER/Line® Shapefiles: County Subdivisions](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions) for Arizona, as provided by the US Census Bureau.

2020 TIGER/Line Shapefiles (machinereadable data files) / prepared by the
U.S. Census Bureau, 2020 [https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions)

## Repository Structure
```
├── README.md
├── biodiversity-phoenix.ipynb
├── .gitignore
└── data/
```
The `biodiversity-phoenix.ipynb` notebook details the steps taken to produce a visualization of BII change from 2017 to 2020, highlighting particular areas that experienced loss.

## Acknowledgments

Thank you to Professor Carmen Galaz-García ([@carmengg](https://github.com/carmengg/carmengg) on GitHub) for assigning this project as a part of EDS 220.
