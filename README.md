# 🏥 Medicare Fraud Detection Dashboard (2024)

## 📌 Project Overview
Analyzed 2024 Medicare Part D data to detect suspicious billing patterns 
using machine learning and data visualization.

**4,499 suspicious records identified across 51 states**

## 🔗 Live Dashboard
👉 [View on Tableau Public](https://public.tableau.com/app/profile/dheeraj.royal.galla/viz/Medicare-Fraud-Detection-2024/Medicare-Fraud-Detection-2024)

## 🛠️ Tools Used
- **Python** — Pandas, Scikit-learn (Isolation Forest, KMeans)
- **SQL** — SQLite for data analysis
- **Tableau Public** — Interactive dashboard
- **Data Source** — CMS Medicare Part D 2024

## 🔍 Key Findings
- California, Texas & Florida = top fraud hotspots
- OxyContin flagged at $686 avg cost/claim vs $18 normal baseline
- 4 distinct fraud clusters identified
- Opioid billing anomalies detected across 51 states

## 📊 Dashboard Preview
![Dashboard](dashboard/screenshot.png)

## 🚀 How to Run
1. Clone this repo
2. Open `notebooks/fraud_detection.ipynb` in Google Colab
3. Upload `data/suspicious_medicare_2024.csv`
4. Run all cells

## 📁 Project Structure
```
├── data/                  # Dataset
├── notebooks/             # Python analysis
├── dashboard/             # Tableau workbook
└── README.md
```
