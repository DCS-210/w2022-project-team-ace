Project proposal
================
Team ACE

``` r
library(tidyverse)
library(broom)
```

## 1. Introduction

Our research question is “How does increasing global temperatures
measured by city predict the number of natural disasters in the same
area?” Our data for global temperatures by city was found using kaggle’s
climate change database. Our data ranges from 1750 to 2015, and has 32
columns representing variables with information regarding min, max, and
average land temperature.

Sub topics:

Global temp and wildfires Global temp and droughts Global temp and
flooding Global temp and hurricanes

``` r
#Import us disaster declarations data
disaster_data <- readr::read_csv(file = "../data/us_disaster_declarations.csv")
```

    ## Rows: 62547 Columns: 22

    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (9): fema_declaration_string, state, declaration_type, incident_type, d...
    ## dbl  (8): disaster_number, fy_declared, ih_program_declared, ia_program_decl...
    ## dttm (5): declaration_date, incident_begin_date, incident_end_date, disaster...

    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

## 2. Data

## 3. Data analysis plan
