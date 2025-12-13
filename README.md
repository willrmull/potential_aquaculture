# Identifying Areas of Potential Aquaculture in the Western US

**Author** William Mullins \| Date: December 10, 2025

### About

This repository supports a spatial suitability analysis to identify regions in the western United States with environmental conditions favorable for farming oysters or blue mussels based on sea surface temperature and water depth.

### Contents

*Data Folder Was Not Pushed*

```         
potential_aquaculture
└───README.md
└─── potential_aquaculture.qmd 
└───.gitignore
    └───data
        └───average_annual_sst_2008.tif
        └───average_annual_sst_2009.tif
        └───average_annual_sst_2010.tif
        └───average_annual_sst_2011.tif
        └───average_annual_sst_2012.tif
        └───depth.tif
        └───wc_regions_clean.shp
```

### Data Access

-   [NOAA Pathfinder Sea Surface Temperature Data](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php): Data from this is used to find the five-year average of sea surface temperature data from 2008-2012, providing a baseline for temperature analysis along the western US coast.

-   [NOAA Bathymetry Data](https://www.gebco.net/data-products/gridded-bathymetry-data#area): High-resolution ocean depth measurements used to identify suitable depths for shellfish cultivation.

-   [West Coast Regional Boundaries](https://www.marineregions.org/eez.php): Spatial boundaries defining the Exclusive Economic Zones (EEZs) for California, Oregon, and Washington, used to calculate suitable habitat area by region.

### **References**

National Oceanic and Atmospheric Administration. (2023). NOAA CoastWatch Pathfinder Sea Surface Temperature Dataset.[**https://podaac.jpl.nasa.gov/dataset/AVHRR_PATHFINDER_L3_V52**](https://podaac.jpl.nasa.gov/dataset/AVHRR_PATHFINDER_L3_V52)

National Centers for Environmental Information. (2023). Gridded Bathymetry Data.[**https://www.ncei.noaa.gov/access/gridded-bathymetry-data**](https://www.ncei.noaa.gov/access/gridded-bathymetry-data)

NOAA Fisheries. (2023). West Coast Regional Boundaries.[**https://www.fisheries.noaa.gov/west-coast/marine-protected-areas/west-coast-regional-boundaries**](https://www.fisheries.noaa.gov/west-coast/marine-protected-areas/west-coast-regional-boundaries)

Food and Agriculture Organization. (2022). The State of World Fisheries and Aquaculture.[**https://www.fao.org/3/ca9229en/ca9229en.pdf**](https://www.fao.org/3/ca9229en/ca9229en.pdf)
