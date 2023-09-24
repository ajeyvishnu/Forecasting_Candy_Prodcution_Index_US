# Forecasting Candy Production Index in the US

**Author:** Ajay Vishnu Addala
**Date:** 09/22/2023

## Introduction

This project aims to forecast the monthly production of candy in the United States using time series forecasting techniques. The dataset used for this analysis contains the Industrial Production Index for Candy (IPG3113N) from October 2012 to the present.

## Data Source

- Data Source: [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/series/IPG3113N)
- Dataset: IPG3113N.csv
- Data Dictionary:
  - Date: Year, Month, and Date during which the data was recorded.
  - IPG3113N: Production Index for Candy in the US.

## Research Question and Hypothesis

**Research Question:** What is the best method to forecast the given time series data?

**Hypothesis:** The ARIMA (AutoRegressive Integrated Moving Average) method will provide the most accurate forecast for this time series data, as it accounts for both trend and seasonality.

## Data Exploration and Analysis

### Time Series Plot

A time series plot was created to visualize the monthly production of candy in the US. It revealed both trend and seasonality in the data.

### Decomposition

Time series decomposition separated the data into trend, seasonal, and residual components. This helped us better understand the underlying patterns.

### Forecasting Models

Four forecasting methods were tested:

1. Naive Method
2. Simple Exponential Smoothing
3. Holt-Winters Method
4. ARIMA Model

Each method was evaluated based on its accuracy and residual analysis. 

### Model Comparison

Model accuracy was compared using Mean Error (ME) and Root Mean Squared Error (RMSE). The ARIMA model had the lowest error values, indicating it was the best-performing model.

## Conclusion

Based on the analysis, the ARIMA model is recommended to forecast US candy production. It provided the most accurate forecasts and had well-behaved residuals. The forecast suggests an increase in candy production over the next one to two years.

For detailed code and analysis, please refer to the [RMarkdown file](forecast_candy_production.Rmd) and the generated [HTML report](forecast_candy_production.html).

---

**Note:** This README provides a summary of the project. For a more in-depth analysis, please refer to the RMarkdown and HTML files in the repository.

