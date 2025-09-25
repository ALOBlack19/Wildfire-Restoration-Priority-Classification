# Forest Fire Restoration Prediction – British Columbia

---
## Overview
This project applies machine learning and geospatial analysis to predict priority areas for forest restoration in British Columbia, Canada.  
The focus is on integrating historical fire records, climate data, elevation, and land cover to assess restoration needs and guide ecological recovery planning.
--- 

## Objectives
- Process and clean fire, climate, and land cover datasets  
- Generate predictive models for fire restoration priorities  
- Map predictions for 2026 with geospatial visualizations  
- Support ecological recovery and rewilding strategies  
---

## Repository Structure


├── environment.yml       # Conda environment file
├── notebooks/            # Jupyter notebooks for data processing & analysis
├── src/                  # Scripts for preprocessing, modeling, and mapping
├── results/              # Processed outputs and figures
└── README.md             # Project description

---

## Data Sources
Raw data is not stored in this repository to avoid large file sizes.  
You can access the original datasets from the following sources:

### Climate and Weather
- [Historical Climate Data – Environment Canada](https://climate.weather.gc.ca/historical_data/search_historic_data_stations_e.html?searchType=stnProv&timeframe=1&lstProvince=BC&optLimit=yearRange&StartYear=2015&EndYear=2025&Year=2025&Month=9&Day=12&selRowPerPage=25)  
- [Canadian Climate Summaries](https://climate.weather.gc.ca/prods_servs/cdn_climate_summary_e.html)  

### Wildfires
- [BC Wildfire Perimeter & Fire Points (BC Government)](https://governmentofbc.maps.arcgis.com/apps/webappviewer/index.html?id=c36baf74b74a46978cf517579a9ee332)  
- [National Fire Database (NFDB) – Natural Resources Canada](https://cwfis.cfs.nrcan.gc.ca/datamart/download/nfdbpoly)  

### Administrative Boundaries
- [Regional Districts – Legally Defined Administrative Areas of BC](https://catalogue.data.gov.bc.ca/dataset/regional-districts-legally-defined-administrative-areas-of-bc)  
- [Administrative Boundaries of BC – Boundary Locations](https://catalogue.data.gov.bc.ca/dataset/legally-defined-administrative-areas-of-bc-boundary-locations)  
- [Municipalities – Legally Defined Administrative Areas of BC](https://catalogue.data.gov.bc.ca/dataset/municipalities-legally-defined-administrative-areas-of-bc)  
- [StatCan Census Boundary Files (2011 RNF-FRR)](https://www12.statcan.gc.ca/census-recensement/alternative_alternatif.cfm?l=eng&dispext=zip&t=lrnf000r24a_e.zip&k=%20%20%20289136&loc=/census-recensement/2011/geo/RNF-FRR/files-fichiers/lrnf000r24a_e.zip)  

### Land Cover
- [Land Cover – GeoBase (1:250,000)](https://catalogue.data.gov.bc.ca/dataset/other-land-cover-1-250-000-geobase-land-cover/resource/4e1ccbf3-63bb-4bbe-b91c-d5ac0d3ab36c)  

### Communities and Population
- [Canadian Population Data – Open Canada](https://open.canada.ca/data/en/dataset/055919c2-101e-4329-bfd7-1d0c333c0e62/resource/de8a365d-6326-4013-a661-7647e5996c55)  

---

## Installation
Clone the repository and create the Conda environment:

```bash
git clone https://github.com/ALOBlack19/Wildfire-Restoration-Priority-Classification-.git
cd <your-repo>
conda env create -f environment.yml
conda activate fire_restore_env
```

## Usage

Run the analysis using Jupyter:

```bash
jupyter notebook
```

Explore the notebooks in the `notebooks/` directory for data preprocessing, modeling, and mapping.

## Results

The project outputs include:

* Restoration priority classification for fire sites
* Geospatial maps of 2026 predictions
* Analytical insights connecting fire history, climate, and landscape features

## License

This project is licensed under the MIT License. See `LICENSE` for details.

```
---