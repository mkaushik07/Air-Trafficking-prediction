Air Passenger Traffic Forecasting with ARIMA

Overview
This project involves forecasting air passenger traffic using the ARIMA (AutoRegressive Integrated Moving Average) model. The objective is to predict future passenger volumes based on historical data, helping to understand trends and make informed strategic decisions.

Project Details
ARIMA Model Development
Data Transformation: Converted time series data to achieve stationarity using moving averages and differencing techniques.
Parameter Optimization: Utilized ACF (AutoCorrelation Function) and PACF (Partial AutoCorrelation Function) plots to determine optimal parameters (p, d, q) for the ARIMA model.
Model Performance: Achieved a Mean Absolute Error (MAE) of 0.112, Mean Squared Error (MSE) of 0.020, and Root Mean Squared Error (RMSE) of 0.140, indicating high accuracy in forecasts.
Forecasting and Trend Analysis
Forecasting: Projected air passenger traffic trends over the next 5 years using the ARIMA model.
Results: Identified a significant upward trend in passenger volume, providing insights into future demand and assisting in strategic planning.
Files Included
forecasting_model.py: Python script containing the implementation of the ARIMA model, including data preprocessing, model fitting, and forecasting.
