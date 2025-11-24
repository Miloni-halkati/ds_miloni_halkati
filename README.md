# 📘 Trader Behavior vs Market Sentiment — Data Science Assignment  
**Candidate:** *Miloni Halkati*  
**Role Applied:** *Junior Data Scientist – Trader Behavior Insights*  

---

## 🔍 1. Project Overview

This project aims to analyze how **trader behavior** changes across different **market sentiment regimes** (Fear, Neutral, Greed) by combining:

- **Hyperliquid Historical Trader Data**
- **Bitcoin Fear & Greed Index**

The analysis explores how profitability, volume, starting positions, and risk-taking vary with sentiment.  
All work was performed in **Google Colab**, adhering to the exact folder structure required.

---

## 📂 2. Repository Structure

```text
ds_miloni_halkati/
│
├── notebook_1.ipynb                # Data cleaning, preprocessing, timestamp parsing, merging
├── notebook_2.ipynb                # Exploratory analysis, aggregations, visualizations, insights
│
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   └── trader_with_sentiment.csv     # Final merged dataset from Notebook 1
│
├── outputs/
│   ├── volume_sentiment.png          # Total volume vs sentiment
│   ├── avg_pnl_sentiment.png         # Average PnL vs sentiment
│   └── avg_position_sentiment.png    # Avg position size vs sentiment
│
├── ds_report.pdf                     # Final report containing visuals & insights
└── README.md                         # Project documentation
⚙️ 3. Methodology Summary
3.1 Data Collection & Understanding
Loaded Hyperliquid trader dataset with execution-level trade records

Loaded Fear & Greed sentiment dataset

Performed schema validation and inspected structure

3.2 Data Cleaning (Notebook 1)
Standardized all column names to snake_case

Converted UNIX timestamps to human-readable datetime formats

Added date_only column to enable merging

Cleaned formatting issues (e.g., exponential notation, strings, missing values)

Verified numeric columns:

execution_price

size_usd

size_tokens

closed_pnl

3.3 Sentiment Engineering
Simplified granular sentiment labels into:

Fear

Neutral

Greed

Merged sentiment data with trade data using date_only

3.4 Exploratory Data Analysis (Notebook 2)
Computed grouped metrics for each sentiment class:

Average PnL

Median PnL

Total PnL

Total Trading Volume (USD)

Average Starting Position Size

Trade Count

Created visualizations to highlight differences across sentiments.

📊 4. Key Insights
4.1 Trading Volume Trends
Trading volume is significantly higher during Greed periods

Indicates stronger activity and confidence when sentiment is positive

4.2 Profitability Patterns
Average and median PnL metrics vary across sentiments

Greed shows higher volatility in outcomes

Fear tends to produce more stable but lower-return behavior

4.3 Position Size Behavior
Position sizes increase during Greed

Suggests higher risk appetite and aggressive strategy deployment

4.4 Risk & Behavior Dynamics
Fear periods → conservative behavior

Greed periods → more aggressive, larger trades

Neutral → baseline steady behavior

📈 5. Visual Outputs (from outputs/ folder)
Included visualizations:

volume_sentiment.png
avg_pnl_sentiment.png
avg_position_sentiment.png

Each chart illustrates differences in trader behavior across sentiment regimes.

🧪 6. How to Reproduce
Open notebook_1.ipynb in Google Colab

Mount Google Drive

Run all cells to generate:

Copy code
trader_with_sentiment.csv
Open notebook_2.ipynb

Run all cells to generate visual outputs in outputs/

Refer to ds_report.pdf for the full written analysis

📑 7. Deliverables Included
✔ Final merged dataset
✔ Two Colab notebooks
✔ Visual output images
✔ Polished PDF report
✔ Professional README

🏁 8. Conclusion
This project demonstrates the strong correlation between market sentiment and trader behavior, highlighting how sentiment shifts influence volume, position sizing, and profitability.
The insights can directly support sentiment-aware trading strategies, risk adjustment, and performance optimization within Web3 trading environments.

👤 9. Candidate Information
Name: Miloni Halkati
Position: Applicant — Junior Data Scientist (Trader Behavior Insights)
Tools Used: Python, Pandas, NumPy, Matplotlib, Google Colab
Date: 24-11-2025
