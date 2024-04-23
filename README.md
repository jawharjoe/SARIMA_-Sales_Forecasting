# SARIMA_-Sales_Forecasting
An in-depth time series analysis repository containing a Jupyter Notebook that demonstrates the application of the SARIMA model to forecast weekly sales data.


## Data Import and Preprocessing
- Dataset loaded from CSV, containing weekly sales data from 2008 to 2021.
- Data split into training and testing sets, with 7.5% as test size.

## Exploratory Data Analysis
- Time series plot generated to show sales trend.
- Augmented Dickey-Fuller test conducted, p-value ~ 1.10e-15, indicating stationarity.

## Model Selection
- Fitted range of SARIMA models to training data.
- Best model selected based on Akaike Information Criterion (AIC), lowest AIC: 14016.79.

## Model Diagnostics
- Diagnosed using plots of standardized residuals, histogram, normal Q-Q, and correlogram.
- Residuals are normally distributed, suggesting good fit.

## Forecasting
- Model used to forecast future sales for 52 steps ahead.
- Forecasted values compared with observed sales, showing close match.

## Model Evaluation
- Performance evaluated using MAPE, MAE, and RMSE:
  - MAPE: 0.4593
  - MAE: 24095.55
  - RMSE: 138524.43

## Conclusion
- SARIMA model effective in forecasting weekly sales.
- Can be used for future sales predictions, aiding in planning.
