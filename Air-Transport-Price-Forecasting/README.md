# Forecasting Passenger Air Transport Prices in the Euro Area

## Project Overview

This project evaluates multiple time series forecasting
models to predict passenger air transport prices across
19 Euro Area countries.

The objective was to identify a reliable forecasting
model that accounts for historical trends, seasonal
patterns, and structural changes.

## Dataset

- Source: Federal Reserve Economic Data (FRED)
- Indicator: Harmonized Index of Consumer Prices (HICP)
- Frequency: Monthly
- Historical period: June 2009 – December 2025
- Holdout period: January 2024 – December 2025
- Forecast horizon: 12 months

## Tools Used

- Microsoft Excel
- Excel Solver
- ForecastX

## Methodology

1. Explored historical data to identify trends and seasonality.
2. Identified a structural break in April 2022.
3. Applied a mean shift adjustment.
4. Performed time series decomposition.
5. Evaluated multiple forecasting models.
6. Compared forecast accuracy using RMSE and MAE.
7. Developed a 12-month forecast.

## Model Performance

| Forecasting Model | RMSE | MAE |
|---|---:|---:|
| Seasonal Naïve Model 1 | 6.86 | 5.20 |
| Seasonal Naïve Model 2 | 6.01 | 4.30 |
| Triple Exponential Smoothing | 8.30 | 6.41 |
| Non-Seasonal ARIMA (0,1,0) | 5.86 | — |
| Seasonal ARIMA | 9.57 | — |

## Key Findings

- Passenger air transport prices exhibit strong seasonality
  and an underlying upward trend.
- A structural shift in April 2022 affected the reliability
  of forecasting models.
- Seasonal Naïve Model 2 achieved competitive forecasting
  accuracy while capturing recurring seasonal patterns.
- More complex forecasting models do not necessarily
  produce better predictions.

## Final Recommendation

Seasonal Naïve Model 2 was recommended for short-term
forecasting due to its competitive accuracy and ability
to capture seasonal fluctuations.

## Business Applications

- Pricing strategy
- Budgeting and financial planning
- Seasonal demand planning
- Operational decision-making
- Market trend analysis

## Limitations

External economic shocks and future structural changes
may affect forecast reliability.

A model parameter was optimized using the holdout period,
limiting its independence as a test set. Future analysis
could use a separate validation and testing period.

## Academic Context

MGTSC 405 – Forecasting

Alberta School of Business | University of Alberta

Winter 2026

