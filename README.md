# 🌫️ Air Quality Time Series Forecasting

A time series forecasting project focused on predicting future air quality levels using deep learning models.

## 🧠 Project Overview

This project explores historical air quality data and builds forecasting models to predict future pollutant levels such as **PM2.5**, **NO2**, **O3**, etc. Using deep learning architectures, the goal is to provide early warnings for poor air conditions and support data-driven environmental policies.

Key components:

- 📊 Exploratory Data Analysis (EDA)
- ⏱️ Feature engineering for time series structure
- 🔮 Forecasting models using deep learning
- 📈 Evaluation and visualization of model predictions
  
---

## 🧪 Models Used

- ✅ **LSTM (Long Short-Term Memory)**

---

## ✅ Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Visual comparison of predicted vs actual series

---
## 📊 Evaluation Summary

### 🔹 Baseline Model

| Target          | MSE       | MAE       | MAPE     | R² Score |
|------------------|------------|------------|------------|-----------|
| AT (°C)         | 0.4633    | 0.5000    | 1.6194%  | 0.9345   |

### 🔹 Modified Model (Improved)

| Target          | MSE       | MAE       | MAPE     | R² Score |
|------------------|------------|------------|------------|-----------|
| AT (°C)         | 0.4176    | 0.4630    | 1.4914%  | 0.9410   |

✅ The **Modified Model** shows improvement across all key metrics:
- **Lower MSE** and **MAE** indicate better predictive accuracy.
- **MAPE** decreased, showing better percentage error performance.
- **R² Score** increased from **0.9345 ➝ 0.9410**, indicating improved model fit.

