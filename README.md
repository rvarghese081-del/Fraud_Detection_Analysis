# Fraud_Detection_Analysis
Fraud Detection Analysis on Banking Transactions | Python, Excel &amp; Power BI Dashboard

## 📌 Project Overview
This project focuses on detecting fraudulent financial transactions using data analysis and machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), model building, and visualization of key insights.

The goal is to identify patterns in fraudulent transactions and help improve decision-making in financial systems.

---

## 🎯 Objectives
- Perform data cleaning and exploratory data analysis (EDA)
- Analyze banking transaction data to identify fraud patterns
- Build an interactive dashboard for fraud monitoring
- Generate actionable insights from data

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Machine Learning (XGBoost, Scikit-learn)
- Power BI (for dashboard visualization)
- Jupyter Notebook
- Excel

---

## 📂 Project Structure
fraud-detection-analysis-dashboard/
│
├── data/
│ └── dataset.csv
│
├── notebooks/
│ └── fraudDetectionAnalysis.ipynb
│
├── dashboard/
│ ├── fraud_dashboard.pbix
│ └── dashboard.png
│
├── README.md

---

## 🔍 Data Analysis (Python - Jupyter Notebook)

The following steps were performed:

- Data cleaning and preprocessing  
- Handling missing values  
- Exploratory Data Analysis (EDA)  
- Identifying fraud patterns and trends  
- Data visualization using charts and graphs

---

## 📊 Dataset Description

The dataset contains financial transaction records with features such as:

- Transaction type
- Transaction amount
- Old and new balances (sender & receiver)
- Transaction time (step)
- Fraud label (isFraud)

---

  ## 🔍 Exploratory Data Analysis (EDA)
  
- Checked missing values and data types
- Analyzed distribution of transaction types
- Compared fraud vs non-fraud transactions
- Identified correlations between features
- Generated automated profiling report

---

## 🤖 Model Building

- Used XGBoost Classifier for fraud detection
- Handled imbalanced data
- Split dataset into training and testing sets
- Trained model on resampled data

  ---
## 📈 Model Evaluation

Evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
  
Focused on improving recall to reduce missed fraud cases

---

## 📊 Model Performance

| Model               | ROC AUC  |
| ------------------- | -------- |
| Random Forest       | 0.999987 |
| Logistic Regression | 0.986193 |
| XGBoost             | 0.999965 |

---

## 📊 Dashboard Features (Power BI)

The dashboard includes:

### 🔹 KPI Metrics
- Total Transactions  
- Fraud Transactions  
- Fraud Percentage  
- Total Transaction Amount  

### 🔹 Visualizations
- Fraud vs Non-Fraud (Pie Chart)  
- Fraud by Category (Bar Chart)  
- Transaction Trends Over Time (Line Chart)  

### 🔹 Filters
- Date filter  
- Transaction type  
- Category filter  

---

## 📈 Key Insights
- Fraud happens when there are sudden changes in balance at certain times.
- Fraud mostly occurs in specific transaction types like transfer and cash out.
- Fraud transactions show incorrect or unusual balance updates.
- Fraud happens more during certain time periods.
- The data has more normal transactions than fraud, so the model may miss fraud cases.
  
---

## 📷 Dashboard Preview

![Dashboard](dashboard/dashboard.png)

---

## 🚀 Conclusion
This project demonstrates how combining data analysis and visualization can help detect fraud patterns and support better decision-making.

---

## 📎 Files Included
- Dataset (CSV)  
- Jupyter Notebook (.ipynb)  
- Power BI Dashboard (.pbix)  

---

## 🔗 Future Improvements
- Apply machine learning models for fraud prediction  
- Deploy dashboard for real-time monitoring  
- Automate data pipeline  
