# chocolate-Sales-Analysis-
Python-based analysis and machine learning on chocolate sales data to uncover business insights, top performers, and sales trends.

# 🍫 Chocolate Sales Analysis – Python Portfolio Project

This project analyzes chocolate sales data across multiple regions and products. The goal is to derive actionable business insights and apply machine learning models to predict sales performance.

---

## 📊 Business Goals

- Identify top-performing salespersons, countries, and products
- Analyze seasonal/monthly sales trends
- Calculate average revenue per box
- Predict product category using Random Forest and Decision Tree models

---

## 🗃️ Dataset Columns

- `Sales Person` – Name of the salesperson  
- `Country` – Where the sale occurred  
- `Product` – Type of chocolate  
- `Date` – Date of sale  
- `Boxes Shipped` – Quantity  
- `Amount` – Total sale amount

---

## 🧼 Data Preprocessing

- Cleaned currency values from `Amount`
- Parsed `Date` into datetime format
- Derived `Month` and `DayOfWeek`
- Encoded categorical features for modeling

---

## 🔍 Exploratory Data Analysis

- **Top Sales by Salesperson** (Bar chart)
- **Sales Distribution by Country**
- **Monthly Revenue Trends**
- **Most Popular Products**

---

## 🧠 Machine Learning Models

### 🎯 Random Forest Classifier
- Predicts product category based on region, boxes shipped, etc.
- Accuracy: **~1.82%**
- Issue: Too many unique product categories → model failed to generalize

### 🌳 Decision Tree Classifier
- Targets: `High`, `Medium`, `Low` sales categories
- Accuracy: **~32.2%**
- Balanced results across classes
- Visualized with `plot_tree()`

---

## 🛠️ Tech Stack

- **Python**: Pandas, Matplotlib, Seaborn, scikit-learn  
- **ML Models**: Random Forest, Decision Tree  
- **Visualization**: Bar plots, tree diagrams  
- **IDE**: Jupyter Notebook / VS Code

---

## 📄 Files Included

- `chocolate_sales_analysis.py` – Main code file  
- `Chocolate Sales.csv` – Dataset  
- `Chocolate_Sales_Report.docx` – Full report  


---
