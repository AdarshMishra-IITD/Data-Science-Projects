# Objective: Predicting 12 months of data of Accedental death in USA using Time Series Analysis 

The dataset is provided with 2 columns:
- Month, Accidental deaths in USA

## Approach:

- Visualise the Time series
- Decomposing into trend, seasonal, cyclical and noise components
- Analyze the seasonality of a Time Series: additive and multiplicative.
- Check stationarity of data - Rolling Mean, ADCF Test(Augmented Dickey–Fuller test)
- Stationarize Time series - first differencing, log transformation and exponatial transformation
- Plot ACF/PACF charts and find optimal parameters and find the optimal value of p,d,q
- Auto Arima for estimating the optimal parameter 
- Build Time series models according to data- ARIMA, SARIMA
- Make predictions
- MAPE,SMAPE as evaluation metric
