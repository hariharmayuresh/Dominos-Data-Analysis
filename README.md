# 🍕 Domino's Delivery Time Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📊 Metric to be Tested  
**🎯 95th Percentile on Order Delivery Time should be less than 30 minutes**

---

## 📝 Project Summary

This analysis evaluates Domino's delivery performance for the month of **March** using order timestamp data.

| Metric                     | Value         |
|---------------------------|---------------|
| Total Deliveries          | 15,000        |
| On-Time Deliveries (≤ 30 mins) | 14,443        |
| Late Deliveries (> 30 mins)     | 557           |
| Average Delivery Time      | ~17.5 minutes |
| Delivery Performance       | **96.29%**    |

> ✅ **Conclusion**: The 95th percentile SLA is met. Domino’s is performing well based on the metric.

---

## 📁 Files Included

- `📘 Dominos_data_Analysis.ipynb`: Code + visualizations + summary
- `📄 dominos_data.csv`: Raw dataset with timestamps

---

## 📈 Tools & Libraries Used

- 🐍 Python (Pandas, Matplotlib)
- 🧠 Jupyter Notebook
- 📉 Data Cleaning & Aggregation
- 📊 Visualization (Pie Charts, Summary Tables)

---

## 📌 Key Insights

- 96.29% of deliveries met the SLA of 30 minutes.
- Only 557 pizzas were late and were likely delivered free.
- The system appears robust and efficient with fast average delivery times.

---

## 🧪 Future Enhancements

- ⏱️ Analyze hourly traffic & performance dips
- 🤖 Build a model to predict potential late deliveries
- 📦 Track dispatch times and bottlenecks in real-time

---

## 🖼️ Dashboard Layout Suggestion (for future development)

- **KPI Cards:** Total Orders, On-Time %, Avg Time
- **Pie Chart:** On-Time vs Late
- **Bar Graph:** Delivery Time by Hour of Day
- **Map (optional):** Area-wise delivery performance

You can use `Plotly Dash`, `Streamlit`, or `Tableau` to visualize this.

---

## 🚀 Get Started

```bash
# Clone the repo
git clone https://github.com/yourusername/dominos-delivery-analysis.git
cd dominos-delivery-analysis

# Open the notebook
jupyter notebook Dominos_data_Analysis.ipynb
