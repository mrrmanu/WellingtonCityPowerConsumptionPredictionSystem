# Wellington City Power Consumption Prediction System


## Problem Statement:
Accurate prediction of city power consumption is critical for efficient energy management, reducing costs, and planning for peak demand. The challenge lies in modeling temporal patterns, seasonal effects, and external factors like weather while minimizing prediction error.

## Solution Overview:
Developed an end-to-end machine learning pipeline to forecast Wellington City’s electricity consumption. The system leverages robust preprocessing, feature engineering, and model benchmarking to identify the best-performing algorithms.

## Approach:

### 1.Data Understanding & EDA:

Analyzed historical power consumption trends and seasonal patterns

Identified correlations with weather conditions, holidays, and temporal features

### 2.Data Preprocessing:

Handled missing values and outliers

Feature scaling and encoding of categorical variables

Train-test split preserving temporal order

### 3.Feature Engineering:

Created lag features, rolling averages, and holiday indicators

Incorporated weather data such as temperature, humidity, and wind speed

### 4.Modeling:

Linear Regression (baseline)

Random Forest Regressor

XGBoost Regressor

LSTM for sequential time-series forecasting

### 5.Evaluation:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

Visualized actual vs predicted consumption trends

## Results & Impact:

Random Forest and XGBoost achieved the best performance with low error rates

Seasonal and weather effects captured effectively

Supports city planners in forecasting peak loads and optimizing energy distribution

## Tech Stack Used:

Python

Pandas, NumPy

Scikit-learn, XGBoost

TensorFlow/Keras (for LSTM)

Matplotlib, Seaborn

## Key Engineering Takeaways:

Feature engineering (lag, rolling statistics) is critical for time-series accuracy

Model selection should consider interpretability for city planning decisions

Temporal validation is essential to avoid data leakage
