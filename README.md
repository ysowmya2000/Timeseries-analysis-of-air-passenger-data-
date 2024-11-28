# Timeseries-analysis-of-air-passenger-data
## Project Overview
This project focuses on the time series analysis and forecasting of monthly airline passenger data from 1949 to 1960. Using the SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors) model, the objective is to forecast passenger counts for the next 24 months based on historical data.

## Dataset Information
The dataset provides monthly totals of airline passengers over a span of 12 years (1949-1960). It is commonly used for time series analysis as it exhibits clear seasonal patterns and trends.

## Attributes:
Month: Month and year in YYYY-MM format.

Passengers: Total number of passengers who traveled in that month.

## Project Workflow
### 1. Data Loading
Load and preprocess the dataset to make it ready for time series analysis.

### 2. Data Exploration and Visualization
Visualize the data to understand trends, seasonality, and patterns.

Analyze the dataset using descriptive statistics.

### 3. Stationarity Check
Perform stationarity tests (e.g., ADF test).

Apply differencing if necessary to stabilize the mean of the time series.

### 4. SARIMAX Model Implementation
Use the SARIMAX algorithm to model and forecast.

Hyperparameter tuning to determine the best (p, d, q) and seasonal (P, D, Q, S) values.

### 5. Forecasting
Forecast the next 24 months.
Plot the results and compare them with the historical data.

### 6. Conclusion
Summarize insights, key findings, and the forecast results.

## Libraries Used
- pandas
- matplotlib
- seaborn
- scikit-learn
- statsmodels
## Algorithm
SARIMAX
## Result
- Trend and Seasonality Analysis: Insights into passenger growth trends and seasonal fluctuations over the years.
- Model Performance: Metrics and visualization showing the accuracy of the SARIMAX model.
- Forecast: Passenger count predictions for the next 24 months, plotted alongside historical data for comparison.

### Dataset
https://www.kaggle.com/datasets/rakannimer/air-passengers
