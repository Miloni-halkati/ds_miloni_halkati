<img src="https://cdn-icons-png.flaticon.com/512/993/993928.png" width="28"/> Trader Behavior vs Market Sentiment — Data Science Assignment
👩‍💻 Candidate: Miloni Halkati
📌 Role Applied: Junior Data Scientist – Trader Behavior Insights
📅 Date: 24-11-2025
🔖 Badges
<p> <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/> <img src="https://img.shields.io/badge/Google%20Colab-Executed-yellow?style=for-the-badge&logo=googlecolab"/> <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/> <img src="https://img.shields.io/badge/Report-PDF-red?style=for-the-badge&logo=adobeacrobatreader"/> </p>
<img src="https://cdn-icons-png.flaticon.com/512/9906/9906629.png" width="26"/> Overview

This project investigates how trading behavior—including PnL, position sizing, and volume exposure—varies under different market sentiment regimes:

😨 Fear

😐 Neutral

😁 Greed

Data sources used:

📊 Hyperliquid Historical Trader Data
📈 Bitcoin Fear & Greed Index

The workflow was built entirely in Google Colab, with a clean, modular analysis pipeline.

<img src="https://cdn-icons-png.flaticon.com/512/833/833524.png" width="26"/> Repository Structure
ds_miloni_halkati/
│
├── notebook_1.ipynb               # Cleaning, preprocessing, merging
├── notebook_2.ipynb               # EDA, grouped metrics, graphs
│
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   └── trader_with_sentiment.csv   # Final merged dataset
│
├── outputs/
│   ├── volume_sentiment.png
│   ├── avg_pnl_sentiment.png
│   └── avg_position_sentiment.png
│
├── ds_report.pdf                   # Final report
└── README.md                       # Documentation

<img src="https://cdn-icons-png.flaticon.com/512/680/680345.png" width="26"/> Methodology
1️⃣ Data Understanding

Loaded both datasets into Colab

Explored schema, quality, and anomalies

Identified formatting issues and timestamp inconsistencies

2️⃣ Data Cleaning & Preprocessing

<img src="https://cdn-icons-png.flaticon.com/512/190/190411.png" width="20"/> Performed in: notebook_1.ipynb

✔ Converted UNIX timestamps → datetime
✔ Standardized column names
✔ Created date_only for merging
✔ Cleaned numeric fields (execution_price, closed_pnl, etc.)
✔ Removed invalid & malformed rows
✔ Exported final dataset → trader_with_sentiment.csv

3️⃣ Sentiment Engineering

Mapped sentiment scores to 3 classes: Fear, Neutral, Greed

Joined datasets using date_only

Verified merge integrity & completeness

4️⃣ Exploratory Data Analysis

<img src="https://cdn-icons-png.flaticon.com/512/1828/1828884.png" width="20"/> Performed in: notebook_2.ipynb

Computed:

📌 Avg & Median PnL
📌 Total traded USD volume
📌 Avg position size
📌 Trade counts by sentiment

Generated all plots stored in /outputs.

<img src="https://cdn-icons-png.flaticon.com/512/2328/2328845.png" width="26"/> Key Insights
🚀 1. Greed Drives Aggressive Trading

Higher trade volume

Larger position sizes

Increased risk exposure

😐 2. Neutral Shows Balanced Behavior

Stable and moderate risk-taking

Mid-range PnL and position sizes

😨 3. Fear Leads to Conservative Trading

Fewer trades

Smaller positions

Restrained exposure

📌 4. Clear Sentiment-Behavior Correlation

Sentiment directly affects:

PnL distribution

Trade size

Risk-taking intensity

Market participation

<img src="https://cdn-icons-png.flaticon.com/512/1829/1829387.png" width="26"/> Visual Outputs

All charts are located in /outputs:

📊 volume_sentiment.png — Total volume by sentiment
📈 avg_pnl_sentiment.png — Avg PnL by sentiment
📉 avg_position_sentiment.png — Avg position size by sentiment

Each visualization highlights strong behavioral changes across sentiment states.

<img src="https://cdn-icons-png.flaticon.com/512/992/992651.png" width="26"/> Reproducibility

Follow these steps:

Open notebook_1.ipynb

Mount Google Drive

Run all cells → generates cleaned dataset

Open notebook_2.ipynb

Run all cells → generates plots & insights

View complete report in ds_report.pdf

<img src="https://cdn-icons-png.flaticon.com/512/2965/2965567.png" width="26"/> Deliverables

✔ Cleaned + engineered dataset

✔ Two Colab notebooks

✔ Visual outputs

✔ Final PDF report

✔ Premium GitHub-style README

<img src="https://cdn-icons-png.flaticon.com/512/456/456212.png" width="26"/> Conclusion

The analysis confirms that market sentiment strongly drives trader behavior.
These insights can enhance:

Risk modeling

Strategy timing

Position sizing models

Trader behavior prediction systems

<img src="https://cdn-icons-png.flaticon.com/512/64/64572.png" width="26"/> Candidate Information

👤 Name: Miloni Halkati
🧪 Tools: Python, Pandas, NumPy, Matplotlib, Google Colab
📌 Role: Junior Data Scientist (Trader Behavior Insights)
