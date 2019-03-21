## Online-ARIMA
The ubiquity of time series is a fact of modern-day life: from stock market data to social media information; from search-engine metadata to webpage analytics, modern-day data exists as a continuous flow of information indexed by timestamps.  
ARIMA models are the main time-series long-term forecasting models in many practical applications. In time series trends or dependencies usually change. This requires frequent refitting of the model from scratch or performing additional training. However, fitting ARIMA models to large-scale data (e.g. hourly time series for 10 years) is time consuming. In this case, the online learning approach helps.  

## Objectives
For a real-time application, online modeling is desirable — a self-generating and self-updating forecasting method is desirable for producing a timely forecast. The ARIMA method in time series is an effective means to address a forecast; it has a solid foundation in classical probability theory and mathematical statistics.  
I. Implement the ARIMA online Gradient Descent algorithm.  
II.Compare with common online learning approach:  
  - complete refitting on data of steps [1, t] each step t
  - additional fitting (warm_start) for every new observation
  - rolling-window refitting on [t-h, t] 
