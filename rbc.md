# Introduction to Time Series Analysis in Economics

## What is Time Series Data?
Time series data is a sequence of data points indexed in time order. Examples include GDP, inflation, and stock prices. It’s essential for understanding the dynamic behavior of economic variables.

## Why Time Series?
In economics, time series models allow us to capture trends, seasonality, and cycles in data, making them useful for forecasting.

### Key Concepts:
1. **Stationarity**: A stationary series has a constant mean and variance over time.
   - Example: Real GDP growth in a stable economy can be modeled as a stationary process.

2. **Autoregressive Models (AR)**: These models use previous values of the variable to predict future values.
   $$ y_t = \alpha + \beta y_{t-1} + \epsilon_t $$

3. **Moving Average Models (MA)**: In these models, the forecast depends on past forecast errors.
   $$ y_t = \mu + \epsilon_t + \theta \epsilon_{t-1} $$

## Applications in Economics:
Time series models help economists to:
- Forecast inflation or GDP growth.
- Understand business cycles.
- Analyze the impact of policy changes.
