# Data 200 Graduate Project

## Project members:
* Name: Kalie Knecht
* SID: 3035325996
* Email: kalie@berkeley.edu

## Dataset(s) I’ll be using: 
Topic 2 Dataset A

DATASET A: GENERAL MEASUREMENTS AND STATISTICS
This dataset contains some general statistics and measurements of various aspects of the climate and the environment. You can access all the data here within Dataset_A.zip on DataHub. It includes the following reports:

daily_global_weather_2020.csv contains data on daily temperature and precipitation measurements. To learn how to use the data from this file, please read the following section on the first report.
us_greenhouse_gas_emissions_direct_emitter_facilities.csv and us_greenhouse_gas_emission_direct_emitter_gas_type.csv contain data reported by EPA (Environment Protection Agency) on greenhouse gas emissions, detailing the specific types of gas reported by facilities and general information about the facilities themselves. The dataset is made available through EPA’s GHGRP (Greenhouse Gas Reporting Program).
us_air_quality_measures.csv contains data from the EPA’s AQS (Air Quality System) that measures air quality on a county level from approximately 4000 monitoring stations around the country. (source)
The following subsection contains more details on how to work with the first report on global daily temperature and precipitation:

The first report on daily temperature and precipitation is measured by weather stations in the Global Historical Climatology Network for January to October 2020.

The data in daily_global_weather_2020.csv is derived from the source file at https://www1.ncdc.noaa.gov/pub/data/ghcn/daily/by_year/2020.csv.gz.

To help you get started with a dataset of manageable size, we have preprocessed the GHCN dataset to include only the average temperature and precipitation measurements from stations that have both measurements. Each row in the preprocessed dataset contains both the average temperature and precipitation measurements for a given station on a given date.

If you wish to explore the climate data for a different year, you can use the GHCN_data_preprocessing.ipynb notebook to download and perform the preprocessing described above. Please be advised that depending on the dataset size for a given year, GHCN_data_preprocessing.ipynb may not run on DataHub. We will not be providing infrastructural support for running the notebook, but you are welcome to run it on a different machine you have access to or ask a GSI to dump the data for you.

The data contains only the (latitude, longitude) coordinates for the weather stations. To map the coordinates to geographical locations, the reverse-geocoder package mentioned in the References section might be helpful.

## 2-3 sentence outline:  
I'll be exploring countries which emit the most greenhouse gases vs which areas of the world are more affected by global warming. Additionally I will take a look at how the nuclear energy capacity of each country correlates to their greenhouse gas output. I would also like to explore some radiation data in relation to this second question, which I will obtain from my research group's environmental monitoring stations.
