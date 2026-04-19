# MachineLearning
SeminarProject
# Sales Forecasting Challenge in R

This project contains my solution to a sales forecasting challenge using **R**. The goal is to predict future SKU-level sales based on historical quantities, product characteristics, and calendar information.

## Overview
The analysis combines:
- exploratory data analysis,
- time series methods,
- Prophet forecasting,
- neural networks with Keras,
- XGBoost for machine learning forecasting.

## Data
The project uses three main files:
- `PredictionChallenge_Dates.csv`
- `PredictionChallenge_SKU_Characteristics.csv`
- `PredictionChallenge_SKU_Quantities.csv`

## Methods
Main steps in the project:
- data cleaning and feature engineering,
- aggregation by category, size, and color,
- lag and rolling mean creation,
- weekly time series forecasting,
- benchmark models,
- machine learning and deep learning models,
- final forecast combination.

## Tools
Key packages used:
- `tidyverse`, `dplyr`, `ggplot2`
- `forecast`, `fable`, `prophet`, `tsibble`
- `tidymodels`, `modeltime`, `timetk`
- `keras`, `tensorflow`
- `xgboost`, `caret`

## Output
The final result is an exported forecast file with predicted sales per SKU.

