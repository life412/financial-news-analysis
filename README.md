# Task 2: Quantitative Analysis of AAPL Stock Data

## Overview
In Task 2, we performed quantitative analysis on AAPL stock price data using Python, **TA-Lib**, and **PyNance**. The goal was to calculate technical indicators, visualize trends, and prepare the dataset for further analysis in Task 3.

---

## Folder Structure
ml_projects/
├── notebooks/
│ └── aapl_with_indicators.csv
├── Data/ # Raw CSVs (ignored in GitHub via .gitignore)
├── .gitignore
├── README.md
├── requirements.txt

markdown
Copy code

---

## Steps Completed

### 1. Data Loading
- Loaded AAPL stock price CSV into a Pandas DataFrame.
- Converted the `Date` column to datetime and set it as the index.
- Verified dataset structure:
  - Columns: Date, Open, High, Low, Close, Volume
  - Number of rows: 3774

### 2. Technical Indicators
Using **TA-Lib**, we calculated:
- **Moving Averages**:
  - MA20: 20-day moving average
  - MA50: 50-day moving average
- **Relative Strength Index (RSI)**: 14-day period
- **MACD (Moving Average Convergence Divergence)**:
  - MACD line, signal line, and histogram

These indicators help identify trends, momentum, and potential buy/sell signals.

### 3. Visualizations
- **Close Price + MA20 + MA50**: Trend analysis and moving average crossovers.
- **RSI**: Overbought (70) and oversold (30) levels.
- **MACD**: Momentum analysis with histogram to visualize divergences.
- Optional candlestick chart with moving averages using `mplfinance`.

### 4. Data Output
- Updated dataset with indicators saved as:
notebooks/aapl_with_indicators.csv

markdown
Copy code
- Raw CSV folder `Data/` is ignored in GitHub to prevent pushing large files.

---

## Libraries Used
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `mplfinance` – Visualization
- `TA-Lib` – Technical indicators
- `PyNance` – Financial metrics (optional for further analysis)

---
