# Insurance Claims Analysis & Fraud Risk Detection Dashboard

## 📌 Project Overview

This project analyzes insurance claim data to uncover claim patterns, evaluate policy performance, and identify potentially suspicious claims using business-driven fraud risk indicators. The analysis was performed using SQL, Python, and Power BI to transform raw insurance data into actionable insights.

The project focuses on claim behavior, claim status trends, policy performance, customer demographics, and fraud-risk detection to support data-driven decision-making in the insurance industry.

---

## 🎯 Business Problem

Insurance companies process thousands of claims every year, making it challenging to identify high-risk claims and monitor policy performance.

The objective of this project is to:

* Analyze insurance claim trends and claim outcomes.
* Evaluate claim behavior across policy types and customer segments.
* Identify potentially suspicious claims using fraud-risk indicators.
* Develop an interactive dashboard for monitoring insurance KPIs.

---

## 🛠️ Tools & Technologies

* SQL Server
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power BI
* DAX
* Power Query

---

## 📊 Key Business Questions

### Claims Analysis

* What is the total number of claims filed?
* What is the average claim amount?
* Which policy type generates the highest claim amount?
* Which age group files the most claims?
* What is the distribution of claim statuses?
* How do claim outcomes vary across policy types?

### Fraud Risk Analysis

* Which claims should be flagged as suspicious?
* Which claims belong to the highest risk category?
* Are claims filed shortly after policy issuance?
* Which policy types exhibit higher fraud-risk indicators?
* What is the claim-to-coverage utilization ratio?

---

## 📈 Dashboard Features

### Page 1: Insurance Claims Overview

#### KPIs

* Total Claim Number
* Average Claim Amount
* Claim Settlement Rate
* Claim Rejection Rate
* Average Claim-to-Coverage Ratio

#### Visuals

* Top Claim Amounts
* Claim Amount by Policy Type
* Claim Amount by Age Group
* Claim Status Distribution
* Policy Type vs Claim Status Matrix

---

### Page 2: Fraud Risk Analysis

#### KPIs

* Suspicious Claims
* High-Risk Claims
* Claims Filed Rate
* High-Risk Claim Threshold
* Average Claim-to-Coverage Ratio

#### Visuals

* Premium Amount vs Claim Amount
* Policy Claim Ratio by Policy Type
* Claims by Claim Timing
* High-Risk Claims Investigation Table

---

## 🚨 Fraud Risk Detection Logic

Claims were flagged as suspicious based on business rules:

* Claims filed within 30 days of policy issuance.
* Claims utilizing a high percentage of policy coverage.
* High-value claims exceeding the 95th percentile threshold.

These indicators help identify claims that may require additional review.

---

## 🔍 Key Insights

* Travel policies generated the highest total claim amount.
* Rejected claims accounted for the majority of claim outcomes.
* Customers aged 55+ filed the highest number of claims.
* 340 claims were flagged as suspicious.
* 131 claims were identified as high-risk claims.
* Early claim activity represented a significant fraud-risk indicator.

---

## 📂 Repository Structure

```text
Insurance-Claims-Analysis-and-Fraud-Risk-Detection
│
├── Data
│   └── InsuranceData.csv
│
├── SQL
│   └── Insurance_Claims_SQL_Analysis.sql
│
├── Python
│   └── Insurance_Claims_EDA.ipynb
│
├── PowerBI
│   └── Insurance_Claims_Dashboard.pbix
│
├── Dashboard_Screenshots
│   ├── Insurance_Claims_Overview.png
│   └── Fraud_Risk_Analysis.png
│
└── README.md
```

---

## 📸 Dashboard Preview

Add screenshots of:

* Insurance Claims Overview Dashboard
* Fraud Risk Analysis Dashboard

---

## 👨‍💻 Author

**Kazi Kudrat Ali**

Aspiring Data Analyst skilled in SQL, Python, Power BI, Data Visualization, Exploratory Data Analysis (EDA), and Business Intelligence.

Connect with me on LinkedIn and GitHub to follow my data analytics journey.

