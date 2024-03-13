# Bike Sharing Demand Prediction - Linear Regression Project

This project focuses on exploring and analyzing the Bike Sharing Demand dataset from the Kaggle challenge. The main goal is to apply Exploratory Data Analysis (EDA) techniques and to understand the limitations of Linear Regression models when applied to certain datasets. Throughout this project, we will discover why Linear Regression might not be the best fit for this particular challenge and consider what other models could potentially offer better predictions.

## Project Objective

- To get comfortable with EDA and understand the importance of choosing the right model for the dataset at hand.
- To explore the Bike Sharing Demand dataset and apply Linear Regression, while acknowledging its limitations.

## Data Description

The dataset comprises hourly rental data along with weather and seasonal information. Here are the features included in the dataset:

- `datetime`: hourly date + timestamp
- `season`: 1 = spring, 2 = summer, 3 = fall, 4 = winter
- `holiday`: whether the day is considered a holiday
- `workingday`: whether the day is neither a weekend nor holiday
- `weather`: 1 = Clear, Few clouds, Partly cloudy, Partly cloudy; 2 = Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist; 3 = Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds; 4 = Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- `temp`: temperature in Celsius
- `atemp`: "feels like" temperature in Celsius
- `humidity`: relative humidity
- `windspeed`: wind speed
- `casual`: number of non-registered user rentals initiated
- `registered`: number of registered user rentals initiated
- `count`: number of total rentals

## Instructions

1. **Get the Data**: The dataset can be downloaded from Kaggle or the supplied csv file in the repository.
2. **Exploratory Data Analysis**: Perform EDA to understand the dataset better. This includes creating scatter plots of count vs. temperature, count vs. datetime, and exploring the correlation between temperature and bike rentals.
3. **Feature Engineering**: Create new features from the datetime column, such as extracting the hour of the day.
4. **Building the Model**: Use Linear Regression to model the relationship between temperature and bike rentals, as well as a more comprehensive model including additional features.
5. **Evaluation**: Discuss the performance of the model and its limitations, particularly the assumption of a linear relationship between features and the target variable.
