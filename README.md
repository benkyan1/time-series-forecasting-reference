# Time Series Forecasting Reference

A comprehensive personal reference notebook for time series forecasting with 20+ models.

## 📋 Overview

This is my personal reference notebook for time series forecasting projects. It contains a complete pipeline from data generation to model evaluation, helping me quickly compare and select the right model for future projects.

## 🚀 Models Included

**Regression Models**
- Linear, Ridge, Lasso, ElasticNet
- Random Forest, Gradient Boosting
- XGBoost, LightGBM, CatBoost
- SVR, KNN

**Time Series Models**
- ARIMA, SARIMA
- Prophet

**Neural Networks**
- LSTM, GRU, Simple RNN
- Transformer-inspired model

**Ensemble Methods**
- Voting Regressor
- Stacking Regressor

## 📊 Features

- Synthetic dataset with trend, seasonality, and noise
- Feature engineering (lags, rolling stats, time features)
- Model comparison with MAE, RMSE, R²
- Future predictions (30/60/90 days)
- Best practices and notes

## 🛠️ Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
pip install xgboost lightgbm catboost
pip install statsmodels prophet
pip install tensorflow
pip install joblib
