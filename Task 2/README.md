# Task 2: Predict Future Stock Prices

## Objective
Predict the next day's closing price of a stock based on historical data.

## Dataset
- **Source**: Yahoo Finance via yfinance API
- **Features**: Open, High, Low, Volume
- **Target**: Next day's Close price

## Steps Performed
- Retrieved stock data using yfinance (Apple Inc. - AAPL)
- Preprocessed data and created lag features for next-day prediction
- Trained models:
  - Linear Regression
  - Random Forest Regressor
- Evaluated using RMSE and plotted actual vs predicted prices

## Tools & Libraries
- pandas, yfinance, scikit-learn, matplotlib

## Key Results
- RMSE for Random Forest: 2.3
- Random Forest outperformed Linear Regression for prediction accuracy

