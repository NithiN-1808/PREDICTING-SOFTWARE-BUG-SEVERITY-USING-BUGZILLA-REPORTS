# PREDICTING-SOFTWARE-BUG-SEVERITY-USING-BUGZILLA-REPORTS

This repository contains a comprehensive Time Series Analysis and Forecasting project. The primary objective of this project is to analyze time series data and forecast future values using different time series forecasting models. We cover multiple techniques, including **ARIMA**, **SARIMA**, and **LSTM (Long Short-Term Memory)** models.

## Project Overview

### Objective:
The goal of this project is to perform time series forecasting using historical data. The dataset contains time-based values that we use to predict future values. Time series forecasting is widely applicable in areas like stock market prediction, weather forecasting, demand forecasting, and more.

### Key Features:
- **Data Preprocessing**: Loading and preparing time series data for model training.
- **Exploratory Data Analysis (EDA)**: Visualizing and understanding the trends, seasonality, and patterns in the data.
- **ARIMA Model**: Using AutoRegressive Integrated Moving Average (ARIMA) to model the time series data.
- **SARIMA Model**: Extending ARIMA to handle seasonal data with the Seasonal ARIMA (SARIMA) model.
- **LSTM Model**: Building a deep learning model using Long Short-Term Memory (LSTM) to capture long-term dependencies in the data.
- **Model Evaluation**: Evaluating model performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and visualizing predictions.

---

## Installation

To run the notebooks in this project, you need to have Python installed along with the necessary libraries.

### Requirements:

1. **Python** >= 3.7
2. **TensorFlow** >= 2.0
3. **Keras** (if using a separate Keras installation)
4. **NumPy** >= 1.19.0
5. **Pandas** (for data manipulation)
6. **Matplotlib** (for data visualization)
7. **Seaborn** (for enhanced visualization)
8. **Scikit-learn** (for machine learning models and evaluation)
9. **Statsmodels** (for ARIMA and SARIMA models)
10. **yfinance** (if using stock data from Yahoo Finance)

### Install the dependencies

Run the following command to install all required dependencies:

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn statsmodels yfinance
