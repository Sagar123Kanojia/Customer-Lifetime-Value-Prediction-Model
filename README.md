# 🧮 Customer Lifetime Value (CLV) Prediction

This project aims to predict **Customer Lifetime Value (CLV)** using transaction data from an online retail store. It combines **RFM analysis**, **machine learning with XGBoost**, and **interactive visualizations in Tableau** to provide data-driven insights.

---

## 📂 Files in this Repository

| File | Description |
|------|-------------|
| `CLV_Project.ipynb` | Full machine learning pipeline in Python |
| `Final LTV prediction CSV.csv` | Cleaned dataset with RFM scores, segments, and predicted CLV |
| `Customer Lifetime Value (CLV) Insights & Segmentation.twbx` | Tableau dashboard with CLV visualizations |
| `CLV_Project_Report.pdf` | Detailed project report |
| `README.md` | Project overview, setup, and usage instructions |

---

## 🚀 Project Objectives

- Perform **RFM analysis** on customer transaction data
- Segment customers into meaningful groups (Best, Loyal, Promising, At Risk)
- Predict CLV using an **XGBoost Regressor**
- Visualize results through an **interactive Tableau dashboard**

---

## 🛠️ Tools & Technologies

- **Python**: Pandas, NumPy, Scikit-learn, XGBoost
- **Tableau**: For building dashboards and business-friendly visuals
- **Excel**: Minor use for segment logic
- **Jupyter Notebook**: For model development

---

## 📊 Tableau Dashboard Components

**Title:** *Customer Lifetime Value (CLV) Insights & Segmentation*

1. **Bar Chart** – Top 10 Customers by Predicted CLV  
2. **Scatter Plot** – Recency vs Frequency colored by CLV  
3. **Pie Chart** – Customer segment distribution  
4. **Histogram** – CLV value distribution

📦 Packaged as `.twbx` (Tableau workbook file)

---

## 🧠 ML Model: XGBoost Regressor

- **Features**: Recency, Frequency, RFM_Score, Segment (encoded)
- **Target**: Monetary value (proxy for CLV)
- **Model Performance**:
  - Baseline R² ≈ 0.58
  - XGBoost R² ≈ 0.74

Also includes a **feature importance chart** to interpret results.

---

## 📥 How to Use

1. Clone this repo
2. Open `CLV_Project.ipynb` and run it step-by-step
3. Open `Final LTV prediction CSV.csv` in Tableau
4. Explore insights in the `Customer Lifetime Value (CLV) Insights & Segmentation.twbx`

---

## 📌 Author

**Sagar Kanojia**  
📅 Date: July 17, 2025  
📧 kanojia.sagarkanojia@gmail.com

---

## 📄 License

This project is open-source. Feel free to use it for learning, portfolios, or similar projects.
