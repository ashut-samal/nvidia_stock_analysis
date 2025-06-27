# NVIDIA Stock Market Analysis

This project performs detailed **exploratory data analysis (EDA)** and **time series preprocessing** on historical stock price data of **NVIDIA Corporation**. The goal is to extract meaningful patterns, understand volatility and seasonal behavior, and prepare the data for forecasting.

---

## Key Objectives

- Understand long-term stock price behavior using trend and volatility analysis
- Perform statistical analysis including stationarity testing using the ADF test
- Visualize daily returns, moving averages, trading volume, and seasonal effects
- Prepare the dataset for future forecasting by addressing non-stationarity

---

## Dataset

- **Source:** Historical daily stock prices for NVIDIA: [**Link**](https://www.kaggle.com/datasets/adilshamim8/nvidia-stock-market-history/data)
- **Columns:**
  - `Date`: Trading date
  - `Open`, `High`, `Low`, `Close`: Stock price metrics
  - `Volume`: Daily trade volume

---

## Exploratory Analysis Highlights

- Plotted `Close` price trends and calculated moving averages (30, 90, 200-day)
- Computed and visualized **daily returns**, **cumulative returns**, and **rolling volatility**
- Analyzed **volume trends** and price ranges to identify volatility clusters
- Created correlation heatmaps to evaluate inter-feature relationships
- Investigated **seasonal trends** by month and weekday

---

## Time Series Preprocessing

- Verified non-stationarity for the 'Close' prices.
- Applied **first-order differencing** to remove non-stationarity
- Verified stationarity using the **Augmented Dickey-Fuller (ADF) test**
  - Result: ADF statistic = `-12.64`, p-value = `0.0`

---

## Tech Stack

- **Python**
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Statsmodels`

---
