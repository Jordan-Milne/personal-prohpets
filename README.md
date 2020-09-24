# Coivd-19 Vs My Spending

### Similar to many others, I have been spending a lot of time in my own home and spending less money on restaurants, uber, travelling and entertainment. Out of curiousity, I wanted to forecast what I would likely spend in 2020 using Prophet and compare it to my actuall spending.

#### What is Prophet?
- Prophet is a package developed by Facebook that is used for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

#### The Data
- The data that is used is actually ***my*** credit card transaction history. The values have been scaled down linearly so that my real spending amount is hidden but the trend remains the same.
