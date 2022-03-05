# TEAM ACE DATA

Document of data file names and descriptions. 

Data can also be found in this folder.


## US Temperature Data
File name: US_temps.csv

[Source](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data)

Due to a maximum file size on GitHub of 100mb, the original file for global land temperatures was filtered locally for US location only by `filter(Country == "United States")`.

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

[Source](https://www.kaggle.com/mmcgurr/us-city-population-densities)

- `Index` - Index of observation
- `City` - Describes City of said population density
- `State` - Describes the state the city is in. 
- `Population Density` - Info on the population density of each city 
- `2016 Population` - total population of the city in 2016
- `Land Area` - describes the total size of the city in square miles. 

