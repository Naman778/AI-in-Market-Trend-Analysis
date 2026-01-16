# AI for Market Trend Analysis – Apple Stock Prediction using LSTM

## Overview
This repository contains the final project for the **AI for Market Trend Analysis** course.
The project investigates whether Long Short-Term Memory (LSTM) neural networks can extract
modest predictive signals from financial time series, focusing on Apple Inc. (AAPL).

## Objective
To predict **next-day Apple stock log returns** using:
- Peer-firm returns (Amazon, Google, Meta, Netflix)
- Market-wide returns (S&P 500)
- Macroeconomic indicators (Gold and Crude Oil)

The emphasis is on **directional predictability**, rather than precise price forecasting.

## Data & Preprocessing
Daily financial data were sourced from Yahoo Finance.  
All necessary preprocessing steps — including:
- data cleaning,
- alignment across assets,
- conversion of prices to log returns,
- feature engineering, and
- handling of missing values

have **already been completed**.

The final, model-ready dataset is provided in:

