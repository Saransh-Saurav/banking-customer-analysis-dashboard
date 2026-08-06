# 🏦 Banking Customer Analysis Dashboard

> An end-to-end Banking Analytics project built using **SQL Server, Python, and Power BI** to transform raw banking data into actionable business insights through interactive dashboards.

![Home Dashboard](Images/Home.png)

---

## 📖 Overview

This project analyzes customer banking data to provide insights into loans, deposits, customer engagement, and financial performance.

The workflow covers the complete analytics pipeline:

- SQL Server for data storage and preparation
- Python for exploratory data analysis (EDA)
- Power BI for dashboard development
- DAX for business metrics and KPI calculations

---

## 🎯 Business Objective

Banks handle thousands of customer records across multiple financial products. The objective of this project is to provide decision-makers with an interactive dashboard to monitor:

- Customer demographics
- Loan portfolio
- Deposit portfolio
- Banking relationships
- Customer engagement
- Investment advisor performance
- Income segmentation

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| SQL Server | Data Storage & Cleaning |
| Python | Exploratory Data Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Analysis |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Power BI | Dashboard Development |
| DAX | KPI & Business Metrics |

---

# 📂 Repository Structure

```
banking-customer-analysis-dashboard/

│
├── Dashboard/
│     Banking Dashboard.pbix
│
├── Data/
│     Banking_csv_file.csv
│
├── SQL/
│     create_tables.sql
│     data_cleaning.sql
│
├── Python/
│     Banking_EDA.ipynb
│
├── Images/
│     Home.png
│     Loan Analysis.png
│     Deposit Analysis.png
│     Summary.png
│
├── Report/
│     Banking Report.pdf
│
└── README.md
```

---

# 📊 Dashboard Pages

## 🏠 Home

Provides a high-level overview of banking performance through key financial KPIs.

### KPIs

- Total Clients
- Total Loan
- Total Deposit
- Total Fees
- Total Credit Card Amount
- Total Savings Account Amount

![Home](Images/Home.png)

---

## 💰 Loan Analysis

Analyzes the bank's lending portfolio through interactive visualizations.

### Insights

- Loan distribution by banking relationship
- Loan contribution by nationality
- Business lending
- Credit card balance
- Income band analysis
- Customer engagement analysis

![Loan Analysis](Images/Loan Analysis.png)

---

## 💳 Deposit Analysis

Provides a comprehensive analysis of customer deposits.

### Insights

- Bank Deposits
- Savings Accounts
- Checking Accounts
- Foreign Currency Accounts
- Deposits by nationality
- Deposits by income band
- Deposits by engagement timeframe

![Deposit Analysis](Images/Deposit Analysis.png)

---

## 📈 Summary Dashboard

Combines the most important banking KPIs into a single executive dashboard.

Includes

- Client Count
- Total Loan
- Total Deposit
- Total Fees
- Business Lending
- Bank Deposit
- Foreign Currency
- Customer Engagement

![Summary](Images/Summary.png)

---

## 🔎 Drill Through

Detailed customer-level analysis.

Includes

- Customer Name
- Investment Advisor
- Engagement Length
- Credit Card Balance
- Total Fees
- Nationality Analysis

![Drill Through](Images/Drill Through.png)

---

# 🧹 Data Preparation

The dataset was prepared before visualization using SQL Server and Python.

Performed transformations include:

- Data type corrections
- Feature engineering
- Income Band creation
- Processing Fee calculation
- Customer Engagement calculation
- Engagement Length calculation
- Data validation

---

# 📐 DAX Measures

Key business measures include:

- Total Clients
- Total Loan
- Total Deposit
- Total Fees
- Bank Loan
- Bank Deposit
- Business Lending
- Savings Account
- Checking Account
- Credit Card Balance
- Foreign Currency Amount
- Engagement Length

---

# 📈 Exploratory Data Analysis

Python was used to perform:

- Missing Value Analysis
- Descriptive Statistics
- Distribution Analysis
- Categorical Analysis
- Correlation Analysis
- Data Visualization

---

# 💡 Key Insights

- Private Banking customers contribute significantly to the loan portfolio.
- Mid-income customers account for the largest share of deposits.
- Loan and deposit patterns vary across customer nationalities.
- Customer engagement provides additional context for understanding banking relationships.
- Interactive filters enable dynamic exploration across gender, banking relationship, investment advisor, and time period.

---

# 🚀 Future Improvements

- Connect Power BI to a live SQL Server database.
- Automate scheduled data refresh.
- Add predictive analytics for customer segmentation.
- Deploy dashboards using Power BI Service.
- Expand with additional banking KPIs.

---

# ⭐ If you found this project useful, consider giving it a star!
