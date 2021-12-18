# IEOR 242 Final Project: Bay Wheels Rentals

This repository contains the code for a final project in UC Berkeley, Fall 2021, IEOR 242 taught by Paul Grigas. In this project, we model the number of bicycle rentals per hour in the Bay Wheels service in 2019, with the goal of building robust forecasting models. We also explore the spatiotemporal approach of forecasting bike rental density over time. 

<div align="center">
  <img alt="Thumbnail" src="https://raw.githubusercontent.com/joshuapjacob/bay-wheels-bike-usage/main/thumbnail.png" width="1000" />
</div>

We present code and results for Linear Regression, CART, Random Forest, Gradient Boosting, and Recurrent Neural Network models for total Bay Wheels bicycle rentals per hour. We further provide a more general spatiotemporal analysis with an Random Forest model that aims to predict rentals at each rental location per day.

Contributors: Newton Cheng, Juliette Chevri\`ere, Yiman Hu, Joshua Jacob, & Xingchen Liao

### Reproduce Results
#### Data Collection
Data can be downloaded from
1. [Bay Wheels Lyft Bike Data](https://www.lyft.com/bikes/bay-wheels/system-data)
2. [Meteostat Weather Data](https://meteostat.net/en/station/72494)
3. [California 1990 Census Location Data](https://www.kaggle.com/camnugent/california-housing-prices)

#### Exploratory Data Analysis 
Run `Exploratory Data Analysis.ipynb`

#### Data Cleaning
1. `Run data_preprocessing.ipynb` to add timestamp and zipcode for raw data collected.
2. `Run data_aggregation.ipynb` to aggregate all data to a single dataset.
3. `Run time_series_features.ipynb` to aggregate time series data with the overall dataset.

#### Model Training and Testing
Run `statistical_models.ipynb` and `RNN Model.ipynb` to reproduce the models.

#### Spatiotemporal Analysis 
Run `.ipynb`s in Spatiotemporal Analysis directory

