# Time-series-Data-Analysis
A brief summary about this project
ARIMA steps: 
Check is data stationary 
Hypothesis by Dickey Fuller test  
Null hypothesis: unit root=1 means data is not stationary 
Alternate: data stationary 
Stationary data : mean and standard deviation should be constant 
To check stationarity use DF test 
If p<.05 means H0 reject 
Else: accepted 
Rolling statistics for trend 
If data is not stationary we have to use differencing to make it stationary by differencing 
Differencing : shifting and after differencing will use DF test to check 
AR(p) by PACF 
I(d) by Differencing 
MA(q) by ACF 

 Kaggle Air passenger dataset link used for my project: https://www.kaggle.com/rakannimer/air-passengers

Reference Source: https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6


