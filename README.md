# 📘 Trader Behavior vs Market Sentiment — Data Science Assignment  
**Candidate:** *Miloni Halkati*  
**Role Applied:** *Junior Data Scientist – Trader Behavior Insights*  

---

## 🔍 1. Project Overview

This repository contains my submission for the **Trader Behavior Insights** Data Science assignment.

The objective of this project is to examine how **trader activity**, **profitability**, **risk exposure**, and **trade volume** vary under different **market sentiment regimes** (Fear, Neutral, Greed).  
This analysis uses:

- **Hyperliquid Historical Trader Data**
- **Bitcoin Fear & Greed Index**

All work was completed using **Google Colab**, adhering strictly to the required directory structure and submission guidelines.

---

## 📂 2. Repository Structure

```text
ds_miloni_halkati/
│
├── notebook_1.ipynb                # Data loading, cleaning, preprocessing, merging
├── notebook_2.ipynb                # Analysis, aggregations, charts, insights
│
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   └── trader_with_sentiment.csv     # Final merged dataset generated in Notebook 1
│
├── outputs/
│   ├── volume_sentiment.png          # Total trading volume vs sentiment
│   ├── avg_pnl_sentiment.png         # Average PnL vs sentiment
│   └── avg_position_sentiment.png    # Avg starting position size vs sentiment
│
├── ds_report.pdf                     # Final report with visuals & insights
└── README.md                         # Project documentation
