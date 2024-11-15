# House-Prices-Regression-model
## Overview
Predict house prices using the Kaggle "House Prices: Advanced Regression Techniques" dataset. The goal is to create a model that predicts house prices based on features like property characteristics and neighborhood details.

## Dataset
train.csv: 1460 samples, 81 columns, including SalePrice (target).
test.csv: 1459 samples, 80 columns (no SalePrice).
## Target
SalePrice: The house price.
## Steps

-Load Data: Import data using Pandas.
-Explore Data: Inspect first few rows and summary statistics.
-Handle Missing Values: 
  -Categorical: Fill with mode.
  -Numerical: Fill with median.
-Feature Engineering:
  -Encode categorical variables. 
  -Scale numerical features.
-Model: Build an XGBoost regression model.

## Requirements
### Install dependencies:
!pip install pandas numpy scikit-learn xgboost

##Usage
-Download dataset from Kaggle.
-Run house_price_prediction.ipynb to preprocess data and train the model:
