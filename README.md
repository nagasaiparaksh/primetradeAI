# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader behavior using:

- Bitcoin Fear & Greed Index dataset
- Hyperliquid historical trader data

The goal of this analysis is to uncover patterns between market sentiment and trading performance, identify behavioral trends, and derive actionable insights that can improve trading strategies.

---

## Objectives

- Analyze trader profitability across different market sentiment conditions
- Study trader activity during Fear and Greed periods
- Identify behavioral patterns in trading decisions
- Perform trader segmentation using clustering techniques
- Generate business insights from market psychology and trading data

---

## Datasets Used

### 1. Bitcoin Fear & Greed Index
Contains:
- Date
- Sentiment Classification
- Sentiment Value

### 2. Hyperliquid Historical Trader Data
Contains:
- Account
- Coin
- Execution Price
- Trade Size
- Side
- Closed PnL
- Timestamp
- Transaction Details

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle Notebook Environment

---

## Analysis Performed

### Data Cleaning
- Timestamp parsing
- Missing value handling
- Column normalization
- Dataset merging

### Exploratory Data Analysis
- PnL distribution across sentiment
- Trading activity analysis
- Buy vs Sell behavior
- Trade size analysis
- Correlation analysis

### Advanced Analysis
- Trader clustering using KMeans
- Behavioral segmentation
- Profitability analysis

---

## Key Insights

- Trading activity increases significantly during Greed periods
- Fear periods produce more volatile PnL distributions
- Larger trade sizes are more common during bullish sentiment
- Consistently profitable traders demonstrate disciplined behavior across all sentiment conditions
- Market sentiment strongly impacts trader psychology and risk-taking behavior

---

## Conclusion

The analysis demonstrates that Bitcoin market sentiment plays a major role in shaping trader behavior, profitability, and market participation. Traders who maintain disciplined strategies across varying sentiment conditions tend to perform more consistently over time.

---

## Repository Structure

```text
Primetrade-Assignment/
│
├── notebook/
│   └── primetrade_analysis.ipynb
│
├── report/
│   └── final_report.pdf
│
├── README.md
│
└── requirements.txt
