# Experiment: Time Series Analysis

## Aim

To perform Time Series Analysis on diabetes data and analyze the trend, seasonality, and variations in Glucose levels over time.

## Objective

The objective of this experiment is to understand time-dependent data using visualization, decomposition, moving average smoothing, and ARIMA forecasting techniques.

## Dataset

The experiment uses:

- Diabetes Dataset (`diabetes9.csv`)

## Feature Used

- Glucose

## Topics Covered

- Time Series Analysis
- Time Series Visualization
- Trend Analysis
- Seasonal Analysis
- Residual Analysis
- Moving Average
- Time Series Decomposition
- ARIMA Forecasting

## Methodology

The following steps are performed:

1. Import the required Python libraries.
2. Load the diabetes dataset.
3. Display and inspect the Glucose data.
4. Plot the Glucose levels as a time series.
5. Decompose the time series into:
   - Trend
   - Seasonality
   - Residual
6. Apply a 7-day moving average for smoothing.
7. Split the data into training and testing sets.
8. Build an ARIMA model using the training data.
9. Forecast future Glucose levels.
10. Compare the actual and forecasted values.
11. Visualize the forecasting results.

## Time Series Decomposition

The time series is decomposed into three main components:

- **Trend:** Shows the long-term movement of Glucose levels.
- **Seasonality:** Shows repeating patterns in the data.
- **Residual:** Represents variations that are not explained by trend or seasonality.

## Moving Average

A **7-day Moving Average** is used to smooth short-term fluctuations and identify the overall pattern in Glucose levels.

## ARIMA Model

The **ARIMA (5,1,0)** model is used for forecasting.

The ARIMA model consists of:

- **p = 5** – Autoregressive terms
- **d = 1** – Differencing
- **q = 0** – Moving average terms

## Model Validation

The dataset is divided into:

- **80% Training Data**
- **20% Testing Data**

The ARIMA model is trained using the training data and evaluated by comparing its forecasts with the actual testing values.

## Tools and Technologies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook

## Learning Outcomes

After completing this experiment, the learner will be able to:

- Understand the concept of Time Series Analysis.
- Visualize time-dependent data.
- Identify trend and seasonal components.
- Apply time series decomposition.
- Use moving averages for data smoothing.
- Build an ARIMA forecasting model.
- Generate future predictions.
- Compare actual and forecasted values.
- Interpret time series forecasting results.

## Result

Time Series Analysis was successfully performed on the Glucose levels of the diabetes dataset. Trend, seasonal, and residual components were analyzed, moving average smoothing was applied, and future Glucose levels were forecast using the ARIMA model.

## Conclusion

This experiment demonstrates how **Time Series Analysis** can be used to understand patterns and variations in sequential data. The combination of decomposition, moving average smoothing, and ARIMA forecasting provides useful techniques for analyzing and predicting future values.
