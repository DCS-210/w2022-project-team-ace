# TEAM ACE DATA

Document of data file names and descriptions. 

Data can also be found in this folder.


## US Temperature Data
File name: US_temps.csv

[Source](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data)

Due to a maximum file size on GitHub of 100m, the original file for global land temperatures was filtered locally for US location only by `filter(Country == "United States")`.

- `dt` - date of observation
- `AverageTemperature` - global average land temperature in celsius
- `AverageTemperatureUncertainty` - the 95% confidence interval around the average
- `City` - City of observation
- `Country` - Country of observation
- `Latitude` - Latitude of observation
- `Longitude` - Longitude of observation

## US Disaster Data
File name: us_disaster_declarations.csv

- `Incident type`: The natural disaster event that occurred.
- `Time (in Years)`: Monthly averages of disaster occurrences through the period of several years.


## Wildfire Data
File name: FW_Veg_Rem_Combined.csv

- `Wildfire Count`: Number of reported wildfires.
- `Time (in Years)`: Monthly averages of wildfire occurrences through the period of several years.
- `fire_name` : Name of Fire
- `fire_size`: Size of Fire 
- `fire_size_class`: Class of Fire Size (A-G)
- `stat_cause_descr`: Cause of Fire
- `latitude`:Latitude of Fire
- `longitude`: Longitude of Fire
- `state`: State of Fire
- `discovery_month`: Month in which Fire was discovered
- `putout_time`: time it took to putout the fire
- `disc_pre_year`: year in which the fire was discovered
- `Vegetation`:Dominant vegetation in the areas 
- `fire_magfire_mag`: magnitude of fire intensity (scaled version of fire_size)
- `Temp_pre_30`:temperature in deg C at the location of fire up to 30 days prior
- `Temp_pre_15`: temperature in deg C at the location of fire up to 15 days prior
- `Temp_pre_7`: temperature in deg C at the location of fire up to 7 days prior
- `Temp_cont`: temperature in deg C at the location of fire up to day the fire was contained
- `Wind_pre_30`: wind in m/s at the location of fire up to 30 days prior
- `Wind_pre_15`: wind in m/s at the location of fire up to 15 days prior
- `Wind_pre_7`: wind in m/s at the location of fire up to 7 days prior
- `Wind_cont`: wind in m/s at the location of fire up to day the fire was contained
- `Hum_pre_30`: humidity in % at the location of fire up to 30 days prior
- `Hum_pre_15`: humidity in % at the location of fire up to 15 days prior
- `Hum_pre_7`: humidity in % at the location of fire up to 7 days prior
- `Hum_cont`: humidity in % at the location of fire up to day the fire was contained
- `Prec_pre_30`: precipitation in mm at the location of fire up to 30 days prior
- `Prec_pre_15`: precipitation in mm at the location of fire up to 15 days prior
- `Prec_pre_7`: precipitation in mm at the location of fire up to 7 days prior


## Sea Level Data
File name: sealevel.csv

[Source](https://www.kaggle.com/kkhandekar/global-sea-level-1993-2021)

- `Year` - Year of datum
- `TotalWeightedObservations` - Number of observations taken
- `GMSL_noGIA` - GMSL (Global Isostatic Adjustment (GIA) not applied) variation (mm) with respect to 20-year TOPEX/Jason collinear 
- `StdDevGMSL_noGIA` - Standard Deviation of GMSL (GIA not applied) variation estimate (mm) Adjustment (GIA)
- `SmoothedGMSL_noGIA` - Smoothed (60-day Gaussian type filter) GMSL (GIA not applied) variation (mm)
- `GMSL_GIA` - GMSL (Global Isostatic Adjustment (GIA) applied) variation (mm) with respect to 20-year TOPEX/Jason collinear 
- `StdDevGMSL_GIA` - Standard deviation of GMSL (GIA applied) variation estimate (mm)
- `SmoothedGMSL_GIA` - Smoothed (60-day Gaussian type filter) GMSL (GIA applied) variation (mm)
- `SmoothedGMSL_GIA_sigmaremoved` - Smoothed (60-day Gaussian type filter) GMSL (GIA applied) variation (mm); annual and semi-annual signal 

- `Global Sea Level`: GMSL (Global Isostatic Adjustment (GIA) not applied) variation (mm).
- `Time (in Years)`: Monthly averages of wildfire occurrences through the period of several years.


## US city population density Data
File name: uscitypopdensity.csv

- `City`: Describes City of said population density
- `State`: Describes the state the city is in. 
- `Population Density`: Info on the population density of each city 
- `2016 Population`: total population of the city in 2016
- `Land Area`: describes the total size of the city in square miles. 


