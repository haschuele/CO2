The following section contains snippets of the analysis as UC Berkeley's policy precludes students from sharing lab code or results.

# Overview

We began this lab by introducing the data, history of the topic, and importance of the analysis. We then conducted a time series-focused EDA on the historical data through 1997, including seasonal (pictured below), time series, ACF, and PACF plots.

![CO2 Seasonal Plot](https://github.com/haschuele/CO2/blob/main/CO2%20Seasonal%20Plot.png)

After data cleaning and EDA, we fit linear, quadratic, polynomial, and ARIMA models to the historical CO2 time series data (known as the Keeling Curve). 

![Fitting Models](https://github.com/haschuele/CO2/blob/main/Keeling%20Curve%20Model%20Fitting.png)

We used the models fit on historical data to forecast when CO2 levels would reach certain thresholds. We then used more up-to-date data through 2022 to determine how well our models performed. As can be seen below, our model (blue) failed to capture the accelerated upward trend in the more recent data (red).

![Forecasted vs Actual CO2 Levels](https://github.com/haschuele/CO2/blob/main/Forecasted%20vs%20Actual%20CO2.png)
