# Prioritizing-potential-aquaculture
This repository houses the necessary materials to create two maps and a table showing the Exclusive Economic Zones with the most suitable area for specified marine aquaculture.

## What's in the repository?
The data for this repository is filed under the .gitignore, but can be found in the section below. Code to reproduce this analysis can be found in the `aquaculture_analysis.qmd` file. The pdf file containing the entire workflow and analysis is `aquaculture_analysis.pdf`. The structure of the repository us as follows:

```
EDS223-HW3
└─── README.md
└─── qmd/Rmd/Proj files
└─── aquaculture_analysis.qmd 
|   .gitignore
    └───data
        └─── wc_regions_clean.shp
        └─── depth.tif
        └─── average_annual_sst_2008.tif
        └─── average_annual_sst_2009.tif
        └─── average_annual_sst_2010.tif
        └─── average_annual_sst_2011.tif
        └─── average_annual_sst_2012.tif

```

## Data
The necessary data can be accessed as follows:
- EEZ data coun be found at [Marineregions.org](https://www.marineregions.org/eez.php)
- Bathymetry data can be found at [GEBCO.net](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area)
- SST data can be found on the [NOAA website](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php)

## Authors and current contributors
[Michaela Dennis](https://github.com/michaeladennis).

## References and acknowledgements
#### Data
 “Search SeaLifeBase.” Www.Sealifebase.Ca, https://www.sealifebase.ca. Accessed 5 Nov. 2026.
 
 “NOAA Coral Reef Watch Daily Global 5Km Satellite Coral Bleaching Heat Stress SST Anomaly Product (Version 3.1).” Coralreefwatch.Noaa.Gov, https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php. Accessed 5 Nov. 2026.

 “Gridded Bathymetry Data (General Bathymetric Chart of the Oceans)..” Gebco, https://www.gebco.net/data_and_products/gridded_bathymetry_data/. Accessed 5 Nov. 2026.

 “Marine Regions.” Www.Marineregions.Org, https://www.marineregions.org/eez.php. Accessed 5 Nov. 2026.

