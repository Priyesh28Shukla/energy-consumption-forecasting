# Energy Consumption Forecasting using Time-Series Modeling

This project focuses on forecasting energy consumption using historical power usage data.
It demonstrates an end-to-end time-series machine learning workflow using real-world sensor data.

## Dataset
The dataset is sourced from the UCI Machine Learning Repository and contains minute-level
household electricity consumption readings collected over multiple years.

## Approach
- Converted minute-level readings to hourly averages
- Performed data cleaning and time-based interpolation
- Engineered lag, rolling-window, and time-based features
- Trained baseline and Random Forest regression models
- Evaluated performance using MAE, RMSE, and MAPE

## Results
The Random Forest model outperformed a lag-based baseline, demonstrating the effectiveness
of feature engineering for energy time-series forecasting.

## Tools & Technologies
Python, Pandas, NumPy, scikit-learn, Matplotlib

## Future Work
- Anomaly detection for abnormal energy usage
- Advanced models such as XGBoost or LSTM
- Real-time inference pipeline

