# dutch-house-price-prediction
Predictive modeling of Dutch house prices comparing market values and municipal tax valuations.

# Dutch House Price Prediction

This project analyzes housing prices in a Dutch regional dataset by comparing two target variables: market-based house prices (`retailvalue`) and municipal tax valuations (`taxvalue`).

The analysis includes exploratory data analysis, variable transformation, robust regression models, cross-validation, and random forest models. The goal is to compare how different predictors affect the two price definitions and evaluate the predictive performance of the models.

## Dataset

The analysis is based on *The Utrecht Housing Dataset – example dataset for prediction*, created by Stefan Leijnen and Sieuwert van Otterloo.

The dataset contains 2,000 observations and includes housing characteristics such as house area, lot area, garden size, number of balconies, construction year, bathrooms, energy efficiency, monument status, and location.

## Methods

- Exploratory data analysis
- Log-transformation and standardization of target variables
- Feature engineering
- Variable segmentation using regression trees
- Multiple linear regression
- Robust regression with Huber loss
- Cross-validation
- Random forest models
- Model comparison using R², MAE, MSE, AIC and BIC

## Main objective

The main objective is to compare predictive models for two different definitions of house value:

- `retailvalue`: market-based house price
- `taxvalue`: municipal tax valuation

## Tools

- R
- Linear regression
- Robust regression
- Random forest
- Cross-validation
- Data visualization
