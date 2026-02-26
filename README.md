# taxi-order-forecasting
This project forecasts hourly taxi orders at airports using ML on time-series data. After resampling and feature engineering (lags up to 168h, rolling means), CatBoost achieves best RMSE of 37.30, outperforming Linear Regression, Decision Tree, LightGBM. Enables optimal driver scheduling during peak hours.
