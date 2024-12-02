# SDGE_EV_EDA
This repository performs EDA on DMV and AFDC including osmnx, census data, and more. The data used in these EDAs are extracted from the "etl.ipynb" file

- EDA on AFDC dataset and exploration of osmnx and cenpy are in AFDC_EDA.ipynb
- EDA on DMV dataset is found in DMV_EDA.ipynb

All datasets used in this repository was downloaded from the web or loaded in with an API, here are the links to the AFDC, and DMV data used respectively:

https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/all/

https://data.ca.gov/dataset/vehicle-fuel-type-count-by-zip-code

The zip code shapefile needed to plot on maps can be found here: https://www2.census.gov/geo/tiger/TIGER2024/ZCTA520/

All the packages and dependencies to run the notebooks locally are found in the "environment.yml" file

## Instructions on how to run the code:
Install all dependencies found in the environment.yml file and run etl.ipynb to get the csv data. With that data, you can then run all the code in AFDC_EDA.ipynb and DMV_EDA.ipynb to see the EDA done with the data.
