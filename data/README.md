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
NOTE: only included relevant variables names
File name: us_disaster_declarations.csv

[source](https://www.kaggle.com/headsortails/us-natural-disaster-declarations/version/72)

- `fema_declaration_string`: gives fema code for the disaster
- `disaster_number`: gives the number of the disaster in the order that it occurred in the state.
- `state`: gives the state that the disaster took place in
- `declaration type`: gives the type of declaration that the disaster is associated with
- `declaration date`: gives the date the declaration was made
- `fy_declared`: 
- `incident_type`: records general type of disaster
- `declaration_title`: records type of disaster 
- `ih_program_declared`: records if any ih program was declared
- `ia_program_declared`: records if any ia program was declared
- `pa_program_declared`: records if any pa program was declared
- `hm_program_declared`:records if any hm program was declared
- `incident_begin_date`: records when the incident the date began
- `incident_end_date`: records when the incident ended
- `disaster_closeout_date`: records when the disaster was officially ended
- `designated_area`: Area of impact by disaster

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

[source](https://www.kaggle.com/mmcgurr/us-city-population-densities)


- `Index` - Index of observation
- `City` - Describes City of said population density
- `State` - Describes the state the city is in. 
- `Population Density` - Info on the population density of each city 
- `2016 Population` - total population of the city in 2016
- `Land Area` - describes the total size of the city in square miles. 


