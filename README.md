# Forecasting Website Traffic Case Study

## Overview
This project develops a time series forecasting model to predict website traffic for TheCleverProgrammer.com. The analysis covers visitor data from June 2021 to June 2022, with the goal of understanding traffic patterns and building accurate predictions for future periods.

## Dataset
**Source:** [Forecasting Website Traffic Case Study](https://statso.io/forecasting-website-traffic-case-study/)  
**Time Range:** June 2021 - June 2022  
**Columns:**
- Date (daily timestamps)
- Views (daily website visits)

## Key Analysis

### 1. Exploratory Data Analysis
- Daily traffic visualization showing significant fluctuations
- Identification of peak traffic periods (up to 12,000 views)
- Detection of weekly and seasonal patterns

### 2. Time Series Decomposition
- Multiplicative decomposition into Trend, Seasonality, and Residuals
- Clear upward trend from 7,000 to 9,000 daily views
- Weekly seasonality patterns (5% variation)

### 3. Model Development
- SARIMA model implementation using Python
- 50-day future predictions

## Built with:
| Tools 		|
| -------- 		|
| Jupyter Notebook	|
| Python	   	|
| Pandas		|
| Numpy			|
| plotly		|
| statsmodels |
