# Airline_Passengers_Forecasting

Air Passenger Traffic Forecasting Problem: An airline company has the data on the number of passengers that have travelled with them on a particular route for the past few years. Using this data, they want to see if they can forecast the number of passengers for the next twelve months.
Making this forecast could be quite beneficial to the company as it would help them take some crucial decisions like:
- What capacity aircraft should they use?
- When should they fly?
- How many air hostesses and pilots do they need?
- How much food should they stock in their inventory?

Starting by first exploring the simple forecasting techniques. They are:
  - Naive method
  - Simple average method
After that evaluating the forecast with the popular error measures. They are:
  - MFE, MAE, MAPE
  - MSE and RMSE

After that explored some simple and popular smoothing technique called Simple Moving Average and evaluated the forecast.
Then explored some other advanced smoothing techniques and also evaluated their forecast. They are:
  - Simple Exponential Smoothing 
  - Holt's Exponential Smoothing
  - Holt-Winters's Exponential Smoothing

But do we need more sophisticated techniques to get an effective forecast? Auto Regressive Models can be tried out. Following are the four autoregressive models which are explored and evaluated their forecast:
  - ARMA: This model exhibits the characteristics of an AR(p) and/or an MA(q) process.
  - ARIMA: This method models a time series with trend. It has an embedded parameter that differences and removes the trend and later integrates it into the original series.
  - SARIMA: SARIMA brings all the features of an ARIMA model with an extra feature, seasonality.
  - SARIMAX: SARIMAX models an External variable (promotions, in this case) along with the non-seasonal and seasonal components.

Which model suits the best?
![image](https://user-images.githubusercontent.com/32987284/115161063-2bd97e80-a0b9-11eb-892e-c1553e51a5d6.png)
