# diverse
Code snippets for different applications, mostly related to meteorological data and/or GIS


### scrape_dwd_archive.ipynb
Contains code and examples on how to easily download meteorological data from DWD weather stations.
Saves a lot of manual clicking.

### process_CERRA.ipynb
Contains functions and an example with which CERRA data can be reprojected into a new CRS and specified meteorological variables can be extracted for point locations.
Helps with opening CERRA .grib-files, setting the data to the correct projection and includes functions that enable reprojection or/and extracting data.

### weather_transformations.ipynb
Different functions to calculate meteorological variables from other meteorological variables.
More specifically, it includes two functions to calculate wind speed and wind direction from u- and v- components of the wind, as well as one function to calculate 
the relative humidity from the temperature and the dew point temperature.
