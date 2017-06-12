# FaceBookStockPrediction

## Objective: 
To help investors to take timely decision while buying or selling Facebook stocks
### Brief Description
``` 
•	Stock Prediction for FaceBook by using Time Series models

•	An analysis on FaceBook Stock price is performed and predicted the stock price for the next 10 stock days by using the historical data using ARIMA ans Random Walk time series models.

•	Close Stock price is selected to acquire complete data(Open,High,Low,Close)

•	Various ARIMA and random walk models were built to fit the data

•	Model comparison is done by using the AIC Values
```
## Steps Involved:
```
•	Data acquisition from Yahoo Finance by using quantmod module

•	Exploratory data analysis on the data

	o	Time series plot for Close stock price across time to see trend of the data
	
	o	Observed the stationarity of the data by using Augmented Dickey-Fuller Test
	
			H0 = Not stationary
		
			Ha = Stationary
		
	o	To transform the data to make it as a stationary Box – Cox transformation is used to identify the power value
	
•	Model Identification is done by ACF and PACF plots

•	Model selection is done by comparing various model by their AIC values

•	Compared the estimated values to the original values of the stock price

•	Observed the pattern of residuals in the data

```


