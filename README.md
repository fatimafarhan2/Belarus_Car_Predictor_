# Belarus_Car_Predictor_
Predict car prices in Belarus using machine learning. Features include advanced preprocessing, hyperparameter-tuned models, and insightful visualizations.
Project Overview
This project predicts car prices in Belarus using a dataset of 56,244 entries with 12 attributes such as make, model, year, mileage, fuel type, and more. By leveraging machine learning techniques, the project identifies the key factors influencing car prices and provides accurate predictions.

While inspired by SUKHMAN-SINGH-1612's Data Science Projects, this project introduces additional enhancements, including:

-Advanced preprocessing and feature engineering.
-Hyperparameter tuning of machine learning models.
-Unique insights through custom visualizations and analysis.
Key Features

Dataset:
Contains 56,244 car listings with 12 attributes such as priceUSD, year, mileage(kilometers), and fuel_type.
Dataset sourced from SUKHMAN-SINGH-1612.
Data Preprocessing:

Imputed missing values for numerical and categorical features.
Encoded categorical variables using one-hot and frequency encoding.
Scaled numerical features for better model performance.
Exploratory Data Analysis (EDA):

Explored correlations between features and prices.
Visualized the impact of key attributes such as year, mileage(kilometers), and fuel_type on car prices.
Machine Learning Models:

Built and evaluated models including:
Linear Regression
Ridge Regression
Random Forest
XGBoost (fine-tuned using RandomizedSearchCV).
Achieved a Mean Squared Error (MSE) of ~6.1 million using the optimized XGBoost model.
Feature Importance:

Identified year (or car_age), mileage(kilometers), and volume(cm3) as the most influential features driving car prices.
Technologies Used
Python Libraries:
Data Manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn, xgboost
Tools:
Google Colab for development and training.
