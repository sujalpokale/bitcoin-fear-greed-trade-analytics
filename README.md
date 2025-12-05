# Crypto Sentiment & Trader Behavior Analysis

This project analyzes how Bitcoin market mood (Fear vs Greed) influences actual trading results, risk appetite, leverage behavior, and profitability using Hyperliquid trading data.

## Repository Structure
ds_<your_name>/
├── notebook_1.ipynb
├── csv_files/
├── outputs/
└── README.md

## Objective
- Compare trader actions vs sentiment cycles.
- Evaluate leverage shifts between Fear & Greed windows.
- Determine if sentiment predicts trading outcomes.

## Datasets
1. Hyperliquid Trader Data
2. Bitcoin Fear & Greed Sentiment Index

## Metrics Calculated
- daily closed_pnl_sum
- daily trade_count
- daily leverage_mean (approximate)
- win_rate
- sentiment_num (Fear = 0, Greed = 1)

## Key Insights
- Greed leads to higher leverage but not higher profit.
- Risk appetite increases during Greed cycles.
- 2–3 day lag sentiment is more predictive vs same-day mood.

## Outputs (Charts)
- Daily PnL shaded by Fear/Greed
- Win rate vs leverage movement
- Correlation heatmap
- Sentiment forecast AUC

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn, scikit-learn, gdown, pyarrow

## Author
Sujal Pokale

