# 🚚 Supply Chain Delay Predictor & Root Cause Dashboard

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

A predictive analytics project that identifies **why shipments get delayed** and **who's responsible** — turning a manual, reactive procurement process into a proactive, data-driven one.

## 🎯 Problem

Procurement teams were manually reviewing shipment reports to catch delays after the fact, with no clear visibility into which suppliers or categories were driving the problem.

## 🔍 What This Project Does

- Queried and analyzed **5,000+ shipment records** across 6 product categories and 4 supplier tiers using SQL
- Identified **Tier 3 suppliers as the root cause of 94% of delays**, surfacing approximately **₹42L in annual penalty exposure**
- Engineered **12 predictive features** (lead time variance, supplier history, category risk, etc.)
- Trained a **Random Forest classifier** achieving **0.86 ROC AUC** to predict shipment delay risk before it happens
- Built a **6-panel BI dashboard** that replaced manual procurement reports entirely, saving **~5 hours/week** of analyst effort

## 🛠️ Tech Stack

- **Languages:** Python, SQL
- **Libraries:** Pandas, Seaborn, Scikit-learn
- **Modeling:** Random Forest (ROC AUC: 0.86)
- **Visualization:** 6-panel interactive dashboard

## 📈 Key Results

| Metric | Result |
|---|---|
| Records analyzed | 5,000+ shipments |
| Root cause identified | Tier 3 suppliers → 94% of delays |
| Penalty exposure surfaced | ~₹42L annually |
| Model performance | 0.86 ROC AUC |
| Analyst time saved | ~5 hrs/week |

## 📂 Project Structure

```
supply-chain-delay-predictor/
├── data/               # Raw and cleaned shipment data
├── notebooks/          # EDA, feature engineering, modeling
├── sql/                # Queries for root-cause analysis
├── dashboard/          # BI dashboard files
└── README.md
```

## 🚀 How to Run

```bash
git clone https://github.com/Meghana12073/supply-chain-delay-predictor.git
cd supply-chain-delay-predictor
pip install -r requirements.txt
jupyter notebook
```

## 📌 Key Takeaway

This project moves procurement reporting from **reactive** (finding out about delays after they happen) to **proactive** (flagging high-risk shipments and suppliers before penalties hit).

---
*Part of my data analytics portfolio — [see all projects](https://github.com/Meghana12073)*
