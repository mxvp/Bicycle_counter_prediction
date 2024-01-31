# Bicycle Count Prediction - Ghent, Belgium

## Introduction

Ghent has implemented bicycle counting points throughout the city as part of their mobility research initiative. The policy promotes bicycles as an eco-friendly mode of transportation for sustainable urban mobility. Leveraging nearly three years of historical data gathered at the Coupure counting point, this project aims to predict bicycle counts for the month of July 2023.

![Counter](https://github.com/mxvp/Bicycle_counter_prediction/blob/main/images/coupure.jpg)

## Data

The data used in this project includes historical bicycle count data from https://data.stad.gent and weather data from https://open-meteo.com.

![cyclists](https://github.com/mxvp/Bicycle_counter_prediction/blob/main/images/cyclists.jpg)

## Methodology

XGBoost, the open-source regularizing gradient boosting framework, was employed for predictions based on observed time- and weather-related patterns.

## Results

On the test set for the month of July 2023, an R² value of 0.83 was achieved. This indicates a strong correlation between the predicted and actual bicycle counts during this period.

![Predictions](https://github.com/mxvp/Bicycle_counter_prediction/blob/main/images/predictions.jpg)