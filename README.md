# House Price Prediction

## Team members

- Purbasa Dhal (22052657)
- Neelu Kumari (22052647)
- Parul Kumari (22052652)

This repository contains a machine learning project that predicts house prices using the *KC House dataset*. The goal is to build a regression model to estimate the price of a house based on features such as location, square footage, number of bedrooms/bathrooms, and more.

##  Files

  - KC_HOUSE_PRED.ipynb: Jupyter Notebook with the full workflow including:
  - Data loading and exploration
  - Data preprocessing and feature engineering
  - Model training (Linear Regression, Random Forest, etc.)
  - Evaluation metrics and visualizations
  - kc_house_data.csv: Dataset containing real estate sales data for King County, USA (includes Seattle). It includes house 
    features and sale prices.

##  Dataset Overview

The dataset has 21,613 entries and 21 columns, with the following key features:
- price: Sale price of the house (target variable)
- bedrooms, bathrooms, sqft_living, floors, etc.: Physical features of the house
- zipcode, lat, long: Location information
- date: Date of the sale
- yr_built, yr_renovated: Year of construction and renovation

##  Models Used

- Linear Regression
- Gradient Boosting Regressor

##  Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Visualizations: Residual plots, feature importance, actual vs. predicted plots

##  Requirements

Common Python libraries used (create requirements.txt based on your notebook):
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mpl toolkits

