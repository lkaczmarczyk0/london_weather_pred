# Project: Predicting Temperature in London

## 📌 Overview

This project runs experiments for different regression models predicting the mean temperature, using a combination of sklearn and MLflow.

## 📦 Dataset

- **Source**: `london_weather.csv`
- **Samples**: 15341
- **Features**: 9 numerical + 1 datetime (`date`)
- **Target**: `mean_temp`

## 🧪 Preprocessing

- **Numerical features**:
  - Imputation: `SimpleImputer(strategy='median')`
  - Scaling: `StandardScaler`

## ⚙️ Models

- **Model_1**: `LinearRegression`
- **Model_2**: `DecisionTreeRegressor`
- **Model_3**: `RandomForestRegressor`
