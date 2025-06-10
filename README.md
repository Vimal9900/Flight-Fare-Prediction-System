# ✈️ Flight Fare Prediction System

A machine learning project developed as part of the course **Introduction to Data Science (MAL7011)** at **IIT Jodhpur**, aimed at predicting flight ticket prices based on multiple factors such as airline, travel date, source/destination, and stop details.

## 📚 Project Overview

Flight ticket prices are highly dynamic, fluctuating based on numerous factors including demand, seasonality, and airline policies. Our objective is to build a predictive system using **machine learning** techniques, specifically **XGBoost**, to accurately forecast flight fares and assist users in booking tickets at the best possible time.


## 🎯 Objectives

- Analyze and understand historical flight data.
- Perform feature engineering and preprocessing.
- Train and evaluate machine learning models for regression.
- Optimize hyperparameters using **Optuna**.
- Provide predictions via an interactive web interface.

## 🧪 Tools & Technologies

- Python (pandas, numpy, matplotlib, seaborn, sklearn, xgboost)
- Google Colab
- Optuna (for hyperparameter tuning)
- Scikit-learn Pipelines

## 📁 Dataset

The dataset was sourced from **EaseMyTrip**, focusing on flight bookings between India's top 6 metro cities.  
**Total Samples**: 300,261  
**Features**: Airline, Source, Destination, Date, Stops, Duration, etc.  
**Target**: Ticket Price

## 🔧 Preprocessing & Feature Engineering

- Extracted features like day, month, year from date.
- Transformed categorical columns using one-hot encoding.
- Used Box-Cox for normalizing skewed features.
- Outlier detection and removal (Z-score, IQR methods).

## 📊 Exploratory Data Analysis (EDA)

- Price distributions by airlines, stops, and cities.
- Time series trends in pricing.
- Correlation matrix and skewness/kurtosis analysis.

## 🤖 Model Building

- Regression models explored:
  - Linear Regression
  - Ridge & Lasso
  - Random Forest
  - **XGBoost** (selected as best)
- Evaluation metrics:
  - **MSE**
  - **R² Score**

## 🧠 Hyperparameter Optimization

Utilized **Optuna** for automatic search and tuning of model parameters to improve performance.

## 📈 Model Performance

- The XGBoost model achieved the best results.
- Training and testing errors compared to avoid overfitting.
- Predictions generalized well to new unseen data.

