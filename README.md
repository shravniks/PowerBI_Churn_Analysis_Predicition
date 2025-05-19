# PowerBI_Churn_Analysis_Predicition

# Microsoft SQL Server + Power BI + Machine Learning: Data-Driven Decision System

## 📌 Project Overview
This project integrates Microsoft SQL Server, Power BI, and Machine Learning to create a unified pipeline that supports data storage, visual analysis, and predictive modeling for smart, data-driven decisions.

## 🔧 Tools & Technologies
Microsoft SQL Server: For structured data storage and querying.

Power BI: For building dynamic dashboards and data visualization.

Python (Machine Learning): For data preprocessing, training ML models, and generating predictions.

## ✅ Workflow Summary
### Step 1. Data Collection & Storage
Imported raw data (Csv from Kaggle) into SQL Server.
Performed basic data cleaning & transformation using SQL queries.

### Step 2. Data Analysis & Dashboarding
Connected Power BI to SQL Server database.
Built interactive visual reports (charts, graphs, KPIs).
Built 3 dashboards
Enabled real-time insights using scheduled refresh.

### Step 3. Machine Learning Model
Exported data from SQL Server to Python using pyodbc.
Used scikit-learn to:
Preprocessed data (handle missing values, encode, scale).
Trained predictive models (XGBoost).
Evaluated performance using metrics like accuracy, F1-score, AUC.

### Step 4. Prediction Integration
ML model outputs saved back to SQL Server.
Made a dashboard to visualise predicted values.
