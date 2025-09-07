# Demand Forecasting for Supply Chain Optimization using Machine Learning

## 📌 Project Overview
This project predicts future product sales using past sales data.  
The goal is to help businesses optimize inventory, reduce stockouts, and avoid overstocking.  

We implemented a **Machine Learning model (Linear Regression)** to forecast demand and visualized actual vs predicted sales.

---

## 📊 Dataset
- Columns:  
  - Date → Sales date  
  - Product → Type of product (Shampoo, Soap, Toothpaste, Lotion)  
  - Store → Store where sales happened  
  - Sales → Units sold  

Dataset file: [`sample_sales_dataset.csv`](./sample_sales_dataset.csv)

---

## ⚙️ Steps Implemented
1. Data Loading & Exploration  
2. Visualization (sales trend, sales by product/store)  
3. Forecasting Model (Linear Regression)  
4. Evaluation with MAE & RMSE  
5. Forecasting future sales (next 7 days)  

---

## 📈 Results
- Example Predictions:  
2021-04-11 → 1106.7
2021-04-12 → 1107.0
2021-04-13 → 1107.3
  
- Plots:  
  - Daily sales trend  
  - Sales by product  
  - Forecast vs actual  

---

## 🚀 Tech Stack
- Python (Pandas, NumPy, Matplotlib, Scikit-learn)  
- Google Colab / Jupyter Notebook  

---

## 🎯 Why This Project is Useful
- Demonstrates ML in a **real-world supply chain use case**  
- Helps businesses **predict demand** and plan inventory better  
- Resume-friendly project with data analysis + forecasting  
