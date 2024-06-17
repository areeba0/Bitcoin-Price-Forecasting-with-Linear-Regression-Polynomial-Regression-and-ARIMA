# Bitcoin Price Forecasting with Time Series and Regression Models

## Overview
This repository contains Python scripts demonstrating various models for forecasting Bitcoin daily closing prices. It includes implementations of Linear Regression, Polynomial Regression, and ARIMA (AutoRegressive Integrated Moving Average) models using historical Bitcoin price data.

## Features
- **Data Visualization**: Utilizes Plotly and Matplotlib for interactive and static visualizations of Bitcoin daily closing prices.
- **Model Implementation**: Implements Linear Regression, Polynomial Regression, and ARIMA models for price forecasting.
- **Performance Evaluation**: Evaluates model performance using metrics such as RMSE, MAE, and MAPE. Conducts time series cross-validation for robust evaluation.
- **Residual Analysis**: Analyzes residuals to assess model adequacy and correctness.

## Dependencies
- Python 
- jupyter notebook
- Required Python packages:
  - pandas
  - NumPy
  - matplotlib
  - plotly
  - stats models
  - scikit-learn

# 1. Data Loading and Initial Exploration
- Load Bitcoin historical data from CSV file (BTC-Daily.csv).
- Perform initial data exploration to understand the structure and summary statistics of the dataset.

# 2. Data Visualization
- Visualize Bitcoin daily closing prices using Plotly for interactive line plots.
    ![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/9b5a191e-0eca-4f52-af9b-a064b748c70d)
  
- Plot the trend of closing prices along with the regression lines for Linear and Polynomial Regression models.
  ![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/428a1a19-e2e5-4202-8d6e-842c4ed9bf18)

  ![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/7e0a7500-1e88-4b01-b76e-7c24dee2d451)

  
# 3. Linear Regression
- Convert date to a numerical feature for regression.
- Split data into training and test sets.
- Fit a Linear Regression model, make predictions, and evaluate using metrics like RMSE and R-squared.
- Visualize the actual data points and the regression line.
  
# 4. Polynomial Regression
- Utilize Polynomial Regression to capture nonlinear relationships.
- Choose the degree of the polynomial and fit the model.
- Evaluate performance metrics and visualize the polynomial regression line.

# 5. ARIMA Model
- Test for stationarity using the Augmented Dickey-Fuller (ADF) test.
- Perform differencing if the data is non-stationary.
- Determine the order of the ARIMA model using ACF and PACF plots.
- Fit the ARIMA model, make predictions, and visualize actual vs. predicted values.
- Analyze residuals and plot ACF/PACF of residuals to validate model assumptions.
![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/5a9bf039-f644-4409-b02e-8bf572a6e7bb)

![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/bd23a77e-ad66-4b30-9f85-d77976c415dd)


  
# 6. Model Evaluation and Selection
- Calculate RMSE, MAE, and MAPE for each model (Linear Regression, Polynomial Regression, ARIMA).
- Perform time series cross-validation for Linear and Polynomial Regression models.
- Visualize residuals over time and plot ACF/PACF of residuals for the ARIMA model.
![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/bbb610e6-6af4-4be0-9736-a49a739c8281)

![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/1edad264-26d6-4647-a4c1-18aa807c2251)

![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/f5cd55d4-6467-4ad6-88da-0977fed3ae29)

![image](https://github.com/areeba0/Bitcoin-Price-Forecasting-with-Linear-Regression-Polynomial-Regression-and-ARIMA/assets/136759791/cff25d64-1bfb-4824-9424-2ab37b74a699)


Install the required packages using pip:
```bash
pip install pandas numpy matplotlib plotly statsmodels scikit-learn

