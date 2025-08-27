# 📊 End-to-End Customer Churn Analysis  
### 📌 Summary page  
![Summary Page](https://github.com/AKHILESHsingh1/End-to-End-Customer-Churn-Analysis-Project/blob/main/summay%20sanpshot.png)  

### 📌 Prediction View  
![Prediction View](https://github.com/AKHILESHsingh1/End-to-End-Customer-Churn-Analysis-Project/blob/main/Prediction%20sanpshot.png) 

## 📌 Project Overview  
This project demonstrates a complete **ETL pipeline, Business Intelligence dashboard, and Machine Learning model** to analyze and predict customer churn.  

The goal was to:  
- Visualize & analyze customer data across demographics, accounts, geography, and services.  
- Identify churn drivers and customer segments with high churn risk.  
- Build a **predictive churn model** using **Random Forest**.  
- Deliver **actionable insights** via **Power BI dashboards**.  

---

## ⚙️ Tech Stack  
- **SQL Server (ETL & Data Processing)**  
- **Power BI (Dashboard & Visualization)**  
- **Python (Jupyter Notebook, ML Model)**  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`  

---

## 🗄️ ETL Process (SQL)  
1. **Data Ingestion** – Loaded CSV into SQL Server staging tables.  
2. **Data Cleaning** – Handled nulls, converted datatypes, applied transformations.  
3. **Production Tables** – Created `prod_Churn` for Power BI reporting.  
4. **Views for BI** – Built `vw_ChurnData` and `vw_JoinData` for churn & new joiner analysis.  

---

## 📊 Power BI Dashboard  
Created an interactive dashboard with the following sections:  

- **Summary Metrics:** Total Customers (6K), New Joiners (411), Total Churn (2K, 27%).  
- **Demographics:** Age Group, Gender, Marital Status vs. Churn Rate.  
- **Account Info:** Payment Method, Contract Type, Tenure Group.  
- **Geography:** Top States by Churn Rate.  
- **Services:** Internet Type, Streaming & Add-on Services vs. Churn.  
- **Churn Distribution:** Churn Categories & Reasons.  


---

## 🤖 Machine Learning Model (Random Forest)  
- **Target:** Customer Churn (Churned = 1, Stayed = 0).  
- **Preprocessing:** Label Encoding categorical features.  
- **Train/Test Split:** 80/20.  
- **Model:** Random Forest Classifier (`sklearn`).  
- **Evaluation:** Confusion Matrix, Classification Report, Feature Importance.  
- **Predictions:** Applied to **Joiner dataset** to identify at-risk customers.  

🔮 **Result:** 381 high-risk churners identified.  
 
---

## 📈 Key Insights  
- **Contract Type** (Month-to-Month) customers churn more.  
- **Higher Monthly Charges** correlated with higher churn.  
- **Tenure < 12 months** saw highest churn.  
- **Payment Method** (Mailed Check) showed higher churn rates.  
- Predicted churners mainly fall in **Age 21–40** and **low-tenure groups**.  

---
🏆 Results
✅ Built end-to-end ETL + BI + ML pipeline.
✅ Delivered dashboard for churn analysis (27% churn rate).
✅ Identified 381 predicted churners with Random Forest.
✅ Provided actionable insights for customer retention strategies.
