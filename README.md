# IEOR 242 Final Project: Bay Wheels Rentals

This repository contains the code for a final project in UC Berkeley, Fall 2021, IEOR 242 taught by Paul Grigas. In this project, we attempt to model the number of bicycle rentals per hour in the Bay Wheels service in 2019, with the goal of building robust forecasting models.

Bicycle rental data is available from https://www.lyft.com/bikes/bay-wheels/system-data. We augment the rental data with weather data obtained from https://meteostat.net/en/station/72494, MUNI bus stop data available at https://data.sfgov.org/Transportation/Map-of-Muni-Stops/kgz5-a5r3, and extracted time series features.

We present code and results for Linear Regression, CART, Random Forest, Gradient Boosting, and Recurrent Neural Network models for Bay Wheels bicycle rentals. We further provide a more general spatiotemporal analysis that aims to model rentals at a rental location per day.

Contributors: Newton Cheng, Juliette Chevri\`ere, Yiman Hu, Joshua Jacob, & Xingchen Liao


### Reproduce Experiment
#### Raw Data Collection
1. Weather data
    - Download the weather csv dataset from https://meteostat.net/en/station/72494
2. Location data
    - Download the weather csv dataset from https://data.sfgov.org/Transportation/Map-of-Muni-Stops/kgz5-a5r3
3. Lyft bike data
    - Download the csv files from https://www.lyft.com/bikes/bay-wheels/system-data

#### Data Cleaning
1. Run data_preprocessing.ipynb to add timestamp and zipcode for raw data collected.
2. Run data_aggregation.ipynb to aggregate all data to a single dataset.
3. Run time_series_features.ipynb to aggregate time series data with the overall dataset.


#### Model Training and Testing
1. Run statistical_models.ipynb and RNN Model.ipynb to reproduce the models.


#### Spatiotemporal Analysis 
1. Run .ipynb in Spatiotemporal Analysis directory


#### Exploratory Data Analysis 
1. Run Exploratory Data Analysis.ipynb