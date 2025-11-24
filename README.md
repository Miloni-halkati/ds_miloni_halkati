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

---

---

## ⚙️ 3. Methodology Summary

### **3.1 Data Collection & Understanding**
- Loaded Hyperliquid trade-level dataset  
- Loaded Bitcoin Fear & Greed Index dataset  
- Explored schema, data types, and structural quality  

---

### **3.2 Data Cleaning & Preprocessing (Notebook 1)**

Key steps included:

- Standardizing column names  
- Converting UNIX timestamps to human-readable datetime formats  
- Creating `date_only` for merging datasets  
- Fixing numeric formatting issues  
- Validating numeric fields (`execution_price`, `size_usd`, `size_tokens`, `closed_pnl`)  
- Removing irrelevant characters and inconsistencies  

---

### **3.3 Sentiment Engineering**
- Mapped original sentiment classifications to:
  - **Fear**  
  - **Neutral**  
  - **Greed**  
- Merged sentiment dataset into trade dataset using `date_only`  
- Exported the combined dataset → `trader_with_sentiment.csv`  

---

### **3.4 Exploratory Data Analysis (Notebook 2)**
Computed grouped sentiment-level metrics:

- **Average PnL per trade**  
- **Median PnL**  
- **Total PnL**  
- **Total traded USD volume**  
- **Average starting position size**  
- **Number of trades**  

Generated sentiment-wise charts and behavioral patterns.

---

## 📊 4. Key Insights

### **4.1 Increased Volume During Greed**
Trades are larger and more frequent under positive sentiment, indicating higher risk appetite.

### **4.2 Position Sizes Expand as Sentiment Improves**
Greed sentiment correlates with significantly larger starting positions.

### **4.3 Fear Promotes Conservative Behavior**
Lower volume, smaller positions, and reduced activity highlight cautious trading patterns.

### **4.4 Sentiment-Linked Behavioral Shifts**
Trader behavior varies meaningfully across sentiment regimes—useful for strategy tuning and risk modeling.

---

## 📈 5. Visual Outputs

All generated charts are available in the `outputs/` directory:

- `volume_sentiment.png` — Total volume vs sentiment  
- `avg_pnl_sentiment.png` — Average PnL vs sentiment  
- `avg_position_sentiment.png` — Avg position size vs sentiment  

---

## 🧪 6. Reproducibility

To reproduce analysis:

1. Open `notebook_1.ipynb` in Google Colab  
2. Mount Google Drive and run all cells  
3. Open `notebook_2.ipynb` and run all cells  
4. Charts will be saved automatically inside `outputs/`  
5. Final results are presented in `ds_report.pdf`  

---

## 📑 7. Deliverables Included

- ✔ Cleaned + merged dataset  
- ✔ Two Google Colab notebooks  
- ✔ Visual charts  
- ✔ Comprehensive PDF report  
- ✔ Professional README.md  

---

## 🏁 8. Conclusion

This analysis demonstrates clear behavioral differences among traders across varying sentiment states.  
Incorporating sentiment as a feature can help improve:

- Strategy timing  
- Position sizing models  
- Risk exposure frameworks  
- Predictive behavior modeling  

---

## 👤 9. Candidate Information

**Name:** Miloni Halkati  
**Role:** Applicant – Junior Data Scientist (Trader Behavior Insights)  
**Tools:** Python, Pandas, NumPy, Matplotlib, Google Colab  
**Date:** 24-11-2025

