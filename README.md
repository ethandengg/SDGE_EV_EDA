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
First clone the repository and activate the environment by running

```bash
git clone https://github.com/ethandengg/SDGE_EV_EDA.git
cd SDGE_EV_EDA
conda env create -f environment.yml
conda activate dsc180a
```

Next download the shp file (tl_2024_us_zcta520.zip) in this link: 

https://www2.census.gov/geo/tiger/TIGER2024/ZCTA520/

and put that file in the data folder.

Run etl.ipynb to get the csv data. With that data, you can then run all the code in AFDC_EDA.ipynb and DMV_EDA.ipynb to see the EDA done with the data.


