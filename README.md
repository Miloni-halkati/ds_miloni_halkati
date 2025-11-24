Trader Behavior vs Market Sentiment — Data Science Assignment

Candidate: Miloni Halkati
Role: Junior Data Scientist – Trader Behavior Insights

📘 Project Overview

This project analyzes the relationship between trader behavior and Bitcoin market sentiment using two datasets:

Bitcoin Fear & Greed Index

Hyperliquid Historical Trader Data

The goal is to understand how trading activity (PnL, position size, volume) changes across sentiment regimes — Fear, Neutral, and Greed — and derive insights that can support smarter trading strategies for Web3-native teams.

This repository contains all required deliverables as per the assignment instructions, executed fully in Google Colab.

📁 Repository Structure
ds_miloni_halkati/
│
├── notebook_1.ipynb              # Data loading, cleaning, timestamp parsing, sentiment merge
├── notebook_2.ipynb              # Exploratory analysis, aggregations, visualizations, insights
│
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   └── trader_with_sentiment.csv  # Final merged dataset
│
├── outputs/
│   ├── volume_sentiment.png       # Volume vs sentiment
│   ├── avg_pnl_sentiment.png      # PnL vs sentiment
│   └── avg_position_sentiment.png # Position size vs sentiment
│
├── ds_report.pdf                  # Final report with analysis, charts, and findings
└── README.md                      # Project documentation

⚙️ Methodology Summary
1. Data Preprocessing (Notebook 1)

Cleaned and standardized column names

Parsed UNIX and IST timestamps

Created date_only field for joining datasets

Simplified sentiment classes:

Extreme Fear → Fear

Extreme Greed → Greed

Merged sentiment data into trader dataset

Exported final trader_with_sentiment.csv

2. Analysis & Visualization (Notebook 2)

Performed grouped analysis on:

Average PnL

Median PnL

Total PnL

Total Trading Volume (USD)

Average Starting Position Size

Trade Count

Generated clear visualizations to highlight sentiment-driven behavior patterns.

📊 Key Insights
1️⃣ Trading Volume Rises During Greed

Market optimism leads to higher participation and larger order flow.

2️⃣ Position Sizes Increase in Greed

Traders take more aggressive positions in bullish sentiment environments.

3️⃣ Fear Leads to Conservative Behavior

Lower volume, smaller positions, and steady PnL characteristics appear during Fear periods.

4️⃣ Sentiment Can Guide Risk Management

Behaviors vary meaningfully across sentiment regimes, indicating potential for sentiment-integrated trading models.

🧪 How to Run the Project

Open notebook_1.ipynb in Google Colab

Mount Google Drive

Run all cells to generate the merged dataset

Open notebook_2.ipynb

Run all cells to reproduce charts in the outputs/ folder

Refer to ds_report.pdf for the complete analysis

📑 Deliverables Included

✔ Cleaned and merged dataset

✔ Two well-structured analysis notebooks

✔ Visual outputs

✔ Final detailed PDF report

✔ Professional README documentation

✉️ Candidate Information

Name: Miloni Halkati
Role Applied: Junior Data Scientist – Trader Behavior Insights
Tools Used: Python, Pandas, Matplotlib, Google Colab
Date: 24-11-2025
