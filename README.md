# Time Series Analysis
Time series analysis is used for non-stationary data—things that are constantly fluctuating over time or are affected by time. Industries like finance, retail, and economics frequently use time series analysis because currency and sales are always changing. Stock market analysis is an excellent example of time series analysis in action, especially with automated trading algorithms. Likewise, time series analysis is ideal for forecasting weather changes, helping meteorologists predict everything from tomorrow’s weather report to future years of climate change. Examples of time series analysis in action include:

- Weather data
- Rainfall measurements
- Temperature readings
- Heart rate monitoring (EKG)
- Brain monitoring (EEG)
- Quarterly sales
- Stock prices
- Automated stock trading
- Industry forecasts
- Interest rates

1. [EDA of Tesla Share Price](./notebooks/EDA%20of%20Time%20Series%20Data_Tesla%20Share%20Price.ipynb)

     - Using [Tesla Data](https://www.google.com/search?q=tesla+shaere+price&oq=tesla+shaere+price&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIPCAEQABgNGIMBGLEDGIAEMgkIAhAAGA0YgAQyCQgDEAAYDRiABDIMCAQQABgNGLEDGIAEMgkIBRAAGA0YgAQyCQgGEAAYDRiABDIJCAcQABgNGIAEMgkICBAAGA0YgAQyCQgJEAAYDRiABNIBCDk1MDVqMWo3qAIAsAIA&sourceid=chrome&ie=UTF-8)
  
2. [EDA of Microsoft Share Price](./notebooks/EDA%20of%20Time%20Series_Microsoft.ipynb)

    - Using [Microsoft Share Price](https://www.google.com/search?q=microsoft+share+price&sxsrf=AB5stBjHXaWCTfDv5sikjr1xKtkkLmAfJw%3A1689232224337&ei=YKOvZIiOFP-SseMP0MKMWA&oq=micro+share+price&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAxgAMgYIABAHEB4yBggAEAcQHjIGCAAQBxAeMgYIABAHEB4yBggAEAcQHjIGCAAQBxAeMgYIABAHEB4yBQgAEIAEMgYIABAHEB4yBggAEAcQHjoLCAAQigUQsQMQkQI6CwgAEIAEELEDEIMBSgQIQRgAUABYowdgvxNoAHABeACAAbUBiAGqBpIBAzAuNZgBAKABAcABAQ&sclient=gws-wiz-serp)
  
3. [Airline Passengers Prediction](./notebooks/Airline%20Passenger%20Prediction_ARIMA.ipynb) / [dataset](./datasets/airline_passengers.csv)

   * Using ARIMA and SARIMAX Models
          - ARIMA and SARIMA are great tools for time series analysis. They require data in a ‘long’ format. 
          - By this I mean a collection (preferably a pandas data-frame) of data points where each data point is associated with a time (in pandas this would be a series                with different times forming the index). 
                   * ARIMA stands for auto regressive integrated moving average. 
                   * SARIMAX is similar and stands for seasonal auto regressive integrated moving average with exogenous factors.
