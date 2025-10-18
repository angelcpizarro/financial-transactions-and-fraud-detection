# 💳 Uncovering Risk: Data-Driven Insights from Financial Transactions

This project explores how data analytics can help detect fraudulent activity and understand customer spending behaviour in financial transactions.
Using a dataset of 5 million synthetic transactions, the analysis focuses on identifying trends, behavioural patterns, and anomalies across customers, devices, and payment channels — illustrating how data-driven methods can strengthen fraud detection and customer protection systems.
The full project is documented in Notion, accompanied by an interactive Looker Studio dashboard showcasing the results.

---

## 🎯 Objectives

- Validate and clean a large financial transactions dataset.
- Analyse transaction patterns by time, location, merchant category, transaction type, device, and payment channel.
- Investigate relationships between behavioural scores (spending deviation, velocity, anomaly) and fraud rate.
- Create visual dashboards to communicate insights clearly and effectively.
- Demonstrate an end-to-end data workflow — from data cleaning to insight delivery.

---

## 🛠️ Tools & Technologies

- Google Cloud Storage – dataset hosting
- Google BigQuery (SQL) – data modelling, cleaning, and analysis
- Spreadsheets (Google Sheets) – data preparation for visualisation
- Looker Studio – dashboard visualisation and storytelling
- Notion – project reporting

---

## 📊 Key Insights

- Fraud Rate: Around 3.6% of all transactions were marked as fraudulent — evenly distributed across categories, channels, and locations, consistent with a synthetic dataset.
- Customer Behaviour: Most transactions are low to mid-value, with a right-skewed distribution.
- Device & Channel Usage: Mobile and web transactions dominate, but all devices and payment methods are used in roughly equal measure, representing balanced synthetic data.
- Behavioural Scores: Fraud rates stay stable across all score bands, reinforcing that the dataset was balanced — but illustrating how such metrics (velocity, geo-anomaly, spending deviation) are key signals in real-world fraud systems.
- Overall: The project highlights how a structured data workflow — from SQL exploration to interactive dashboards — can reveal patterns and build foundations for predictive fraud detection.

---
  
📂 Project Structure

```
financial-transactions-and-fraud-detection/
├── sql/
│   ├── data_validation_&_exploration.sql
│   └── customer_behaviour_&_fraud_analysis.sql
├── dashboard_screenshots/
│   ├── dahsboard-page1.png
│   └── dashboard-page2.png
└── README.md
```
---

## 🔗 Project Links

- **Full Project Report (Notion)**: View on [Notion](https://www.notion.so/Uncovering-Risk-Data-Driven-Insights-from-Financial-Transactions-28ddb8544a2680a3b8efcfd02e57a8ab?source=copy_link)
- **Interactive Dashboard (Looker Studio)**: Open [Dashboard](https://lookerstudio.google.com/reporting/bbcd20ae-fc8c-42f9-8ed5-cf5ee38a3b93)

---

## 📌 Status

✅ Completed

---

## 🚀 Next Steps

- Extend the analysis with real-time fraud monitoring concepts or predictive modelling using machine learning.

---

## 🔗 More About Me

Check out more of my work on my [GitHub profile](https://github.com/angelcpizarro) or connect with me on [LinkedIn](https://linkedin.com/in/angelcpizarro).

---

Thank you for visiting!
