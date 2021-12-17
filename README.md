# IEOR 242 Final Project: Bay Wheels Rentals

This repository contains the code for a final project in UC Berkeley, Fall 2021, IEOR 242 taught by Paul Grigas. In this project, we attempt to model the number of bicycle rentals per hour in the Bay Wheels service in 2019, with the goal of building robust forecasting models.

Bicycle rental data is available from https://www.lyft.com/bikes/bay-wheels/system-data. We augment the rental data with weather data obtained from https://meteostat.net/en/station/72494, MUNI bus stop data available at https://data.sfgov.org/Transportation/Map-of-Muni-Stops/kgz5-a5r3, and extracted time series features.

We present code and results for Linear Regression, CART, Random Forest, Gradient Boosting, and Recurrent Neural Network models for Bay Wheels bicycle rentals. We further provide a more general spatiotemporal analysis that aims to model rentals at a rental location per day.
