# Trip Duration Predictor

## Overview
This project aims to predict the travel duration (in seconds) for ride-sharing trips based on ride start/end geospatial coordinates (WGS84) and the departure datetime. The model is evaluated using the Root Mean Squared Error (RMSE) metric.

## Data Description
- **train.csv:** Contains ride details with columns:
  - `row_id`: Unique identifier for each trip
  - `start_lng`, `start_lat`: Longitude and latitude of the ride's starting location
  - `end_lng`, `end_lat`: Longitude and latitude of the ride's destination
  - `datetime`: Trip start time (local)
  - `duration`: Actual trip duration in seconds
- **test.csv:** Contains ride details for which predictions are to be made with columns:
  - `row_id`: Unique identifier for each trip
  - `start_lng`, `start_lat`: Longitude and latitude of the ride's starting location
  - `end_lng`, `end_lat`: Longitude and latitude of the ride's destination
  - `datetime`: Trip start time (local)