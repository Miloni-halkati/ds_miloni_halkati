# 🚀 Trader Behavior vs Market Sentiment Analysis  
### *Data Science Assignment – Web3 Trading Team*  
**Author:** *Miloni Halkati*

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Colab](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=google-colab)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Data](https://img.shields.io/badge/Data-Crypto%20Trading%20%2F%20Sentiment-yellow)

A complete analytical project exploring the relationship between **trading behaviour** and **market sentiment** (Fear, Neutral, Greed).  
This study combines **Hyperliquid Trader Data** with the **Bitcoin Fear & Greed Index** to uncover key behavioural and performance patterns.

---

# 📑 Table of Contents

- [✨ Overview](#-overview)
- [📂 Repository Structure](#-repository-structure)
- [🧠 Methodology](#-methodology)
- [📊 Key Insights](#-key-insights)
- [📈 Visual Outputs](#-visual-outputs)
- [🧪 How to Reproduce](#-how-to-reproduce)
- [📄 Deliverables](#-deliverables)
- [🏁 Conclusion](#-conclusion)
- [👩‍💻 Author](#-author)

---

# ✨ Overview

This assignment examines how **traders behave under different market sentiment conditions** by analysing:

- Profitability (PnL)  
- Position sizing  
- Trading volume  
- Activity frequency  
- Risk-taking patterns  

Sentiment is derived from the **Fear–Greed Index**, while behavioural metrics come from **Hyperliquid's historical trading data**.

All work was completed in **Google Colab**, as required.

---
## 📂 Repository Structure

The repository strictly follows the required format:

ds_miloni_halkati/
│
├── notebook_1.ipynb
├── notebook_2.ipynb
│
├── csv_files/
│ ├── fear_greed_index.csv
│ ├── historical_data.csv
│ └── trader_with_sentiment.csv
│
├── outputs/
│ ├── volume_sentiment.png
│ ├── avg_pnl_sentiment.png
│ └── avg_position_sentiment.png
│
├── ds_report.pdf
└── README.md


---

# 🧠 Methodology

### 🔹 1. Data Preparation (Notebook 1)
- Loaded and validated both datasets  
- Cleaned inconsistent formatting  
- Converted UNIX timestamps  
- Created `date_only` column  
- Normalised sentiment labels (Fear / Neutral / Greed)  
- Merged sentiment with trader data  
- Exported final dataset  

### 🔹 2. Exploratory Data Analysis (Notebook 2)
- Grouped traders by sentiment  
- Computed:
  - Avg & median PnL  
  - Total PnL  
  - Total traded volume  
  - Avg starting position  
  - Trade counts  
- Generated 3 main visualisations  

---

# 📊 Key Insights

### 📌 **1. Greed Drives Higher Trading Activity**
Volume spikes significantly during positive sentiment phases.

### 📌 **2. Position Sizes Increase During Greed**
More confidence → more risk-taking.

### 📌 **3. Fear Produces Conservative Trading**
Lower volume, smaller positions, and stable PnL patterns.

### 📌 **4. Sentiment Predicts Behavioural Shifts**
Clear behavioural differences across sentiment regimes, suggesting sentiment-aware strategy potential.

---

# 📈 Visual Outputs

Located inside the `outputs/` folder:

- `volume_sentiment.png`
- `avg_pnl_sentiment.png`
- `avg_position_sentiment.png`

These charts illustrate behavioural variation across sentiment states.

---

# 🧪 How to Reproduce

### **1️⃣ Open notebook_1.ipynb**
- Mount Google Drive  
- Run all cells  
- Generates `trader_with_sentiment.csv`  

### **2️⃣ Open notebook_2.ipynb**
- Run all cells  
- Produces all charts in `outputs/`  

### **3️⃣ Read the full analysis**
- Open `ds_report.pdf`

---

# 📄 Deliverables

- ✔ Cleaned & merged dataset  
- ✔ Two well-structured Colab notebooks  
- ✔ Output charts  
- ✔ Complete PDF report  
- ✔ Professional README  

---

# 🏁 Conclusion

The analysis shows that **market sentiment has a strong influence on trader behavior**.  
Greed leads to aggressive trading, while Fear promotes caution.  
These findings support the use of **sentiment signals** in trading risk models and strategy design.

---

# 👩‍💻 Author

**Miloni Halkati**  
Junior Data Scientist – Trader Behavior Insights  
*Passionate about data science, crypto markets, and behavioural analytics.*
