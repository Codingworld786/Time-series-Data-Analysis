# Time-series-Data-Analysis
<br>

**Key Steps in ARIMA Modeling:**

<br>

1. **Checking for Stationarity:**
   - **Dickey-Fuller (DF) Test:**
     
   - **Rolling Statistics:**
     [For Trend Analysis]
   - **Differencing:**
     [To make data stationary]

<br>

2. **Identifying AR(p), I(d), and MA(q) Orders:**

   - **Autocorrelation Function (ACF):**
     [To find moving average term (q)]
   - **Partial Autocorrelation Function (PACF):**
     [To find AutoRegressive term (p)]
   - **I(d):**
     [Number of differencing]

<br>

3. **Summary of the project:**

ARIMA brief summary about this project
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

MA(q) by ACF ]

<br>

4. **Forecasting:**

 

<br>


 Kaggle Air passenger dataset link used for my project: https://www.kaggle.com/rakannimer/air-passengers

Reference Source: https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6


