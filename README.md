# Feature Engineering & Preprocessing Pipeline

## Project Overview

This project demonstrates feature engineering and preprocessing techniques for housing price prediction using machine learning.

## Objective

To build a complete preprocessing and machine learning pipeline that predicts house prices using housing-related features.

## Dataset

Housing Prices dataset containing numerical and categorical features such as area, bedrooms, bathrooms, location-related indicators, and other house attributes.

## Preprocessing Techniques

* Missing value handling using SimpleImputer
* Numerical feature scaling using StandardScaler
* Categorical feature encoding using OneHotEncoder
* ColumnTransformer to apply transformations to selected columns
* Pipeline to combine preprocessing and model training

## Machine Learning Model

Random Forest Regressor

## Evaluation Metrics

* Mean Absolute Error (MAE)
* R² Score

## Feature Importance

Feature importance is calculated using the trained Random Forest model and displayed as a bar chart.

## Data Leakage Prevention

The dataset is split into training and testing sets before fitting the preprocessing pipeline. The transformations are fitted using training data only.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook
* VS Code

## Files

* `data/Housing.csv` — Dataset
* `notebooks/feature_engineering.ipynb` — Main notebook
* `prediction_results.csv` — Actual and predicted house prices
