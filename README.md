# 📊 Trader vs Sentiment Analysis

Analyze how market sentiment affects trader behavior using the Fear & Greed Index and historical trading data. Generates 📈 visualizations and a 📄 PDF report.

---

## 📝 Project Overview

This project merges trading data with sentiment scores to uncover patterns in **Fear 😨 vs Greed 🤑** periods, performing data cleaning, feature engineering, visualization, and automated reporting.

---

## ✨ Key Features

- 📥 **Data Handling**: Load, clean, and standardize datasets.  
- 🧠 **Sentiment Mapping**: Encode Fear (0) and Greed (1).  
- ⚡ **Feature Engineering**:  
  - Profit Margin = `ClosedPnL / Size`  
  - Risk = `Size × Leverage`  
- 📊 **Aggregations & Visuals**: Trade counts, median size, leverage, boxplots, scatter plots, heatmaps.  
- 💾 **Export Outputs**: Processed CSV files and PDF report.  

---

## ⚙️ Tech Stack

- 🐍 **Python** 3.8+  
- 🐼 **Libraries**: pandas, numpy  
- 📉 **Visualization**: matplotlib  
- 📄 **Reporting**: fpdf  

---

## 🚀 Setup & Run

```bash
pip install pandas numpy matplotlib fpdf
python main.py
```

## 📁 File Structure

ds_Jane_Karunya/
├── fear_greed_index.csv
├── historical_data.csv
├── outputs/
├── csv_files/
├── ds_report.pdf
├── main.py
└── README.md

## ✅ Conclusion

This project shows how market sentiment influences trading outcomes and provides automated reports for easy analysis. 📊📄
