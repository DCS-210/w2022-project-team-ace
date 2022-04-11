# TEAM ACE DATA

Document of data file names and descriptions. 

Data can also be found in this folder.

  
## US Temperature Data
File name: US_temps.csv

[Source](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data)

Due to a maximum file size on GitHub of 100m, the original file for global land temperatures was filtered locally for US location only by `filter(Country == "United States")`.
Columns: 7
Rows: 687289

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

[Source](https://www.kaggle.com/headsortails/us-natural-disaster-declarations/version/72)
Columns: 22
Rows: 62547


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

[Source](https://www.kaggle.com/capcloudcoder/us-wildfire-data-plus-other-attributes)
Columns: 43
Rows: 55375

- `unnamed column 1` - number
- `unnamed column 2` - number
- `fire_name` - Name of Fire
- `fire_size` - Size of Fire (acres)
- `fire_size_class` - Class of Fire Size (A-G)
- `stat_cause_descr` - Cause of Fire
- `latitude` - Latitude of Fire
- `longitude` - Longitude of Fire
- `state` - State of Fire
- `discovery_month` - Month in which Fire was discovered
- `putout_time` - time it took to putout the fire
- `disc_pre_year` - year in which the fire was discovered
- `Vegetation` - Dominant vegetation in the areas 
- `fire_magfire_mag` - magnitude of fire intensity (scaled version of fire_size)
- `Temp_pre_30` - temperature in deg C at the location of fire up to 30 days prior
- `Temp_pre_15` - temperature in deg C at the location of fire up to 15 days prior
- `Temp_pre_7` - temperature in deg C at the location of fire up to 7 days prior
- `Temp_cont` - temperature in deg C at the location of fire up to day the fire was contained
- `Wind_pre_30` - wind in m/s at the location of fire up to 30 days prior
- `Wind_pre_15` - wind in m/s at the location of fire up to 15 days prior
- `Wind_pre_7` - wind in m/s at the location of fire up to 7 days prior
- `Wind_cont` - wind in m/s at the location of fire up to day the fire was contained
- `Hum_pre_30` - humidity in % at the location of fire up to 30 days prior
- `Hum_pre_15` - humidity in % at the location of fire up to 15 days prior
- `Hum_pre_7` - humidity in % at the location of fire up to 7 days prior
- `Hum_cont` - humidity in % at the location of fire up to day the fire was contained
- `Prec_pre_30` - precipitation in mm at the location of fire up to 30 days prior
- `Prec_pre_15` - precipitation in mm at the location of fire up to 15 days prior
- `Prec_pre_7` - precipitation in mm at the location of fire up to 7 days prior


## Sea Level Data
File name: sealevel.csv

[Source](https://www.kaggle.com/kkhandekar/global-sea-level-1993-2021)
Columns: 9
Rows: 702

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
Columns: 6
Rows: 754

- `Index` - Index of observation
- `City` - Describes City of said population density
- `State` - Describes the state the city is in. 
- `Population Density` - Info on the population density of each city 
- `2016 Population` - total population of the city in 2016
- `Land Area` - describes the total size of the city in square miles. 
<<<<<<< HEAD
=======


## Global CO2 data
File name: co2_data.csv

[Source](https://keelingcurve.ucsd.edu/permissions-and-data-sources/)
Columns: 6
Rows: 1346 

This data is not tidy. The first 3 columns are data for Ice cores, the last 3 are Mauna Loa CO2 data.
- `Age_yrBp` - Age in years before present
- `CO2_ppm` - Parts per million CO2
- `Source_ice` - Source core 
- `Date` - Date of data recorded
- `co2_ppm` - Parts per million CO2
- `Source` - Location of data
>>>>>>> beffeaf5b0c58f8743b4e4da6e060ada74c12c82


