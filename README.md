# Daily Sales Forecasting with SARIMA
This project builds a SARIMA model to forecast daily sales for a specific store-item combination.
It includes full EDA, stationarity checks, differencing, model selection via AIC grid search,
residual diagnostics, forecasting evaluation, and business insights.

## Project Structure
- Exploratory Data Analysis
- ACF/PACF analysis
- ADF stationarity test
- Seasonal and non-seasonal differencing
- SARIMA model selection (grid search)
- Residual diagnostics
- 90-day forecasting
- MAE, RMSE, MAPE evaluation


## Results
- Best model: SARIMA(0,1,2)x(1,1,2,7)
- RMSE ≈ 6.1
- MAE ≈ 4.4
- MAPE ≈ 33%
