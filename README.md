Project Title: Trader Behavior vs Market Sentiment — Data Science Analysis
Candidate: Miloni Halkati

🔍 1. Project Overview

This project investigates how trader behavior correlates with overall market sentiment using two primary datasets:

Bitcoin Fear & Greed Index

Hyperliquid Historical Trader Data

The analysis explores whether trader performance (PnL), risk-taking behavior (position size), and activity levels (volume) vary across different sentiment regimes — Fear, Neutral, and Greed.

This assignment fulfills the requirements for the Junior Data Scientist – Trader Behavior Insights role and demonstrates skills in data wrangling, EDA, visualization, and insight generation.

🗂 2. Repository Structure

The submission follows the required standardized format:

ds_miloni_halkati/
│
├── notebook_1.ipynb              # Data loading, cleaning, preprocessing, merging
├── notebook_2.ipynb              # Analysis, visualizations, insights
│
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   └── trader_with_sentiment.csv # Cleaned merged dataset generated in Notebook 1
│
├── outputs/
│   ├── volume_sentiment.png      # Total volume by sentiment
│   ├── avg_pnl_sentiment.png     # Average PnL by sentiment
│   ├── avg_position_sentiment.png# Avg starting position by sentiment
│
├── ds_report.pdf                 # Final professional report with insights
└── README.md                     # Project documentation (this file)


All code was executed and tested in Google Colab, following the instructions.

🧪 3. Methodology Summary
Data Preparation (Notebook 1)

Standardized all column names

Parsed UNIX timestamps and human-readable timestamps

Extracted date_only field for merging

Simplified sentiment categories (Extreme Fear → Fear, Extreme Greed → Greed)

Merged sentiment data with trader data

Exported the final combined dataset

Analysis (Notebook 2)

Computed the following metrics grouped by sentiment:

Average PnL

Median PnL

Total PnL

Total Trading Volume (USD)

Average Start Position Size

Number of Trades

Visualizations were created to highlight trends clearly.

📊 4. Key Insights
1️⃣ Trading Volume Rises During Greed

Traders become more active when sentiment turns positive, indicating higher confidence and risk appetite.

2️⃣ Average PnL Varies by Sentiment

Patterns suggest that trader performance shifts noticeably across Fear, Neutral, and Greed regimes.

3️⃣ Position Sizes Increase in Greed

Traders take larger positions when market sentiment is optimistic, potentially exposing themselves to higher risk.

4️⃣ Fear Periods Show More Controlled Behavior

Lower volume and smaller position sizes indicate cautious trading during negative sentiment.

These signals can help inform position sizing rules, risk thresholds, and sentiment-aware strategy adjustments.

📈 5. Visualizations Included

All visual outputs are available in the outputs/ directory:

volume_sentiment.png — Total trading volume by sentiment

avg_pnl_sentiment.png — Average PnL per trade by sentiment

avg_position_sentiment.png — Average starting position size by sentiment

📑 6. Report

A comprehensive, well-structured written report consolidating all methodology, findings, charts, and strategic insights is included:

ds_report.pdf

🛠 7. How to Reproduce the Analysis

Open notebook_1.ipynb in Google Colab

Mount Google Drive

Run all cells to generate trader_with_sentiment.csv

Open notebook_2.ipynb

Run all cells to produce charts in the outputs/ folder

Refer to ds_report.pdf for consolidated insights

✉️ 8. Candidate Information

Prepared by:
Miloni Halkati

Role: Junior Data Scientist — Trader Behavior Insights
Tools Used: Python, Pandas, Matplotlib, Google Colab
Date: 24-11-2025