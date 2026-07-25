# Sensex Stock Analysis & Forecasting

An end-to-end Python notebook analyzing historical trends of the BSE SENSEX index, performing feature engineering, and building predictive models to forecast price movements.

---

## Overview

This project explores historical price data from the BSE Sensex to identify key volatility patterns, moving average trends, and predictive signals. 

### Key Highlights
- **Data Collection:** Pulled historical daily/monthly Sensex index records using `yfinance` / Yahoo Finance API.
- **Exploratory Data Analysis (EDA):** Visualized historical returns, rolling volatility, daily log returns, and drawdowns.
- **Feature Engineering:** Calculated technical indicators like Simple Moving Averages (SMA 20/50/200), Exponential Moving Averages (EMA), Relative Strength Index (RSI), and MACD.
- **Modeling:** Tested forecasting approaches (Baseline Moving Average, ARIMA/GARCH, and Machine Learning classifiers/regressors) to evaluate directional accuracy.

---

## Requirements & Tech Stack

- **Python:** 3.8+
- **Core Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Finance & Data:** `yfinance`
- **Modeling & ML:** `scikit-learn`, `statsmodels`

---

## Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/InFeRnoVaaa/SENSEX.ipynb.git](https://github.com/InFeRnoVaaa/SENSEX.ipynb.git)
cd SENSEX.ipynb
