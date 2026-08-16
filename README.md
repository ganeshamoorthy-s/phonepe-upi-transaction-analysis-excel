PhonePe UPI Transaction Analysis Dashboard | Excel
Project Overview
<img width="1800" height="627" alt="image" src="https://github.com/user-attachments/assets/555d6de0-c4be-4af3-9f01-5e3bd32992d0" />


<img width="1126" height="622" alt="image" src="https://github.com/user-attachments/assets/7e78c588-fc68-4ec2-a92a-8d0c96b1f8c7" />



This project presents an interactive **UPI Transaction Analysis Dashboard developed using Microsoft Excel**.

The project analyzes **9,467 UPI transactions worth ₹9.47 Cr** covering the period from **2020 to July 2026**.

The purpose of the project is to transform raw transaction records into a structured analytical solution that helps understand **transaction behavior, customer payments, credit/debit activity, spending categories, transaction timing, and business trends**.

The dashboard is designed from a **small-business transaction analysis perspective**, where transaction data can be used to monitor activity and identify patterns without manually reviewing thousands of individual transactions.

---

# Why This Project?

Small businesses can generate a large number of digital payment transactions through UPI.

When transaction records are available as raw data, it can be difficult to quickly answer questions such as:

* How much money was received through the recorded UPI transactions?
* How much was spent?
* When is transaction activity highest?
* Which categories account for more transactions?
* What are the high-value transactions?
* Which days and hours have higher activity?
* How does transaction activity change over time?
* Are customer payments concentrated in particular periods?

Manually checking thousands of transactions is time-consuming.

Therefore, I created an **interactive Excel dashboard to convert raw transaction data into a single decision-support view**.

---

# Business Problem

The main business problem addressed by this project is:

> **How can raw UPI transaction data be transformed into meaningful business insights for faster monitoring and decision-making?**

The project addresses this by combining:

**Raw Transactions → Data Preparation → Categorization → KPI Analysis → Trend Analysis → Dashboard → Business Insights**

---

# Business Purpose

The dashboard is designed to provide a consolidated view of transaction activity.

It helps a business user:

* Monitor transaction volume
* Track recorded credit and debit activity
* Understand customer payment patterns
* Identify spending categories
* Identify high-value transactions
* Understand transaction timing
* Compare monthly and daily activity
* Identify high-activity weekdays and hours
* Reduce manual transaction review
* Support data-driven decision-making

---

# Business Impact

The main impact of this project is **better visibility into transaction activity**.

Instead of reviewing individual transaction records manually, a business user can use the dashboard to quickly understand:

### 1. Transaction Performance

KPI cards provide an immediate overview of:

* Total Transactions
* Total Credit
* Total Debit
* Total Transaction Value
* Average Transaction
* Highest Transaction
* Lowest Transaction

This reduces the time required to understand the overall transaction position.

### 2. Customer Payment Visibility

Customer Payments are separated from other transaction categories.

This makes it easier to analyze recorded customer receipt activity and understand transaction patterns.

### 3. Spending Visibility

Categories such as:

* Home & Groceries
* Food & Hotels
* Petrol & Diesel
* Recharge
* Shopping
* Small-Business Requirements

help identify where recorded transaction activity is concentrated.

### 4. Time-Based Decision Support

Monthly, daily, weekday, and hourly analysis helps identify periods of higher transaction activity.

This can support operational planning and transaction monitoring.

### 5. High-Value Transaction Monitoring

The dashboard highlights high-value transactions so that significant transactions can be identified quickly rather than manually searching through the dataset.

### 6. Reduced Manual Analysis

Instead of manually reviewing thousands of transaction records, users can interact with the dashboard using filters and visualizations.

This improves **analysis efficiency and reporting visibility**.

---

# Key Metrics

| KPI                     |      Value |
| ----------------------- | ---------: |
| Total Transactions      |      9,467 |
| Total Credit            |   ₹6.63 Cr |
| Total Debit             |   ₹2.85 Cr |
| Total Transaction Value |   ₹9.47 Cr |
| Average Transaction     | ₹10,009.42 |
| Highest Transaction     |    ₹66,327 |
| Lowest Transaction      |        ₹29 |

---

# Key Business Questions Answered

The dashboard helps answer:

**Transaction Volume**

* How many transactions were recorded?

**Transaction Value**

* What is the total transaction value?
* What is the average transaction amount?

**Credit and Debit**

* What is the recorded credit amount?
* What is the recorded debit amount?
* How do recorded credit and debit values compare?

**Customer Activity**

* How much recorded activity is related to customer payments?

**Category Analysis**

* Which transaction categories have higher activity?

**Time Analysis**

* Which months have higher transaction activity?
* Which weekdays show higher activity?
* Which hours have higher transaction activity?

**High-Value Transactions**

* What are the largest recorded transactions?

---

# Analysis Performed

## Credit and Debit Analysis

Compared recorded credit and debit transaction values to understand transaction flow within the available dataset.

## Customer Payment Analysis

Analyzed customer-related transactions to understand recorded customer payment activity.

## Category Analysis

Analyzed transactions across business and personal categories to understand transaction purpose.

## Monthly and Daily Analysis

Analyzed transaction values over time to identify trends and changes in activity.

## Weekday Analysis

Compared transaction activity across different days of the week.

## Time-of-Day Analysis

Analyzed transaction activity across different times of the day.

## Hour-Day Heatmap

Used an hour-day heatmap to identify periods where transaction activity is more concentrated.

## High-Value Transaction Analysis

Identified significant transaction values for additional monitoring.

---

# Transaction Categories

Transactions were categorized into:

* Customer Payments
* Friends & Family
* Family Members
* Home & Groceries
* Food & Hotels
* Petrol & Diesel
* Recharge
* Shopping
* Small-Business Requirements
* Other Transactions

---

# Dashboard Features

The Excel dashboard includes:

* KPI Cards
* Credit vs Debit Analysis
* Monthly Transaction Trends
* Daily Transaction Trends
* Weekday Analysis
* Time-of-Day Analysis
* Hour-Day Heatmap
* High-Value Transaction Analysis
* Year Filter
* Month Filter
* Date Filter
* Financial Year Filter

---

# Data Preparation

The transaction dataset was prepared for analysis through:

* Data review
* Date and time standardization
* Credit/debit separation
* Transaction categorization
* Data validation
* Analysis-ready field preparation
* Transaction value checking
* Dashboard-oriented data structuring

---

# Data Interpretation

An important part of this project was understanding that **transaction data must be interpreted within its source and context**.

The dashboard shows the transaction activity available in the analyzed UPI dataset.

For example, if the recorded credit amount is higher than the recorded debit amount, this should **not automatically be interpreted as business profit**.

The dataset may not contain transactions from:

* Bank accounts
* Google Pay
* Paytm
* Other UPI applications
* Cash
* Other payment channels

Therefore:

> **Credit vs Debit in this dashboard represents recorded UPI transaction activity, not complete business revenue, expenses, profit, or loss.**

This is an important data-analysis consideration because a Data Analyst should avoid making conclusions that the available data cannot support.

---

# Data Limitation

This project focuses on the available UPI transaction dataset.

It should not be treated as a complete accounting or Profit & Loss statement.

A complete financial analysis would require additional sources such as:

* Bank transactions
* Other UPI platforms
* Cash transactions
* Accounting records
* Business expenses
* Other payment channels

The dashboard therefore focuses on:

**UPI Transaction Analysis and Business Activity Monitoring**

rather than:

**Complete Business Financial Performance Analysis**

---

# Business Value

The project creates value by converting raw transaction records into a **structured, interactive decision-support dashboard**.

### Before the Dashboard

```text
Thousands of Raw Transactions
          ↓
Manual Review
          ↓
Difficult to Identify Patterns
          ↓
Time-Consuming Analysis
```

### After the Dashboard

```text
Raw Transaction Data
          ↓
Data Preparation
          ↓
Transaction Categorization
          ↓
KPI & Trend Analysis
          ↓
Interactive Dashboard
          ↓
Business Insights
          ↓
Faster Decision Support
```

---

# Key Learning

The most important learning from this project was:

> **A Data Analyst should not only analyze numbers; they should understand the source, context, limitations, and business meaning behind the numbers.**

This project helped strengthen skills in:

* Data validation
* Financial transaction analysis
* Business-context interpretation
* KPI development
* Dashboard design
* Trend analysis
* Data visualization
* Business insight generation

---

# Tools and Skills

**Microsoft Excel**

* Data Cleaning
* Data Validation
* Data Categorization
* Pivot Tables
* Pivot Charts
* Slicers
* KPI Development
* Data Visualization
* Trend Analysis
* Time-Series Analysis
* Heatmap Analysis
* Transaction Analysis
* Financial Data Analysis
* Business Intelligence
* Business Insights
* Decision Support

---

# Future Improvements

The project can be expanded by combining multiple payment channels:

* PhonePe
* Google Pay
* Paytm
* Bank Transactions
* Cash Transactions

Future analysis could include:

* Customer Segmentation
* Business vs Personal Classification
* Customer Contribution Analysis
* Revenue Analysis
* Expense Analysis
* Transaction Frequency
* Customer Behavior Analysis
* Profitability Analysis
* Power BI Dashboard
* Automated Reporting

---

# Conclusion

This project demonstrates how a Data Analyst can convert raw UPI transaction records into a **business-focused analytical solution**.

The complete analysis flow is:

**Raw Data → Data Validation → Categorization → KPI Analysis → Transaction Trends → Customer Analysis → Business Insights → Decision Support**

The key objective was not simply to create an Excel dashboard, but to demonstrate how transaction data can be converted into **actionable business information while maintaining accurate and responsible financial interpretation**.



# Skills Demonstrated

**Data Analysis | Microsoft Excel | FinTech Analytics | Financial Data Analysis | UPI Transaction Analysis | Data Cleaning | Data Validation | KPI Dashboard | Pivot Tables | Slicers | Data Visualization | Transaction Monitoring | Trend Analysis | Business Intelligence | Business Insights | Decision Support**



> **“Converted raw transaction records into an interactive decision-support dashboard, improving transaction visibility, reducing manual review, and enabling faster identification of business-relevant transaction patterns.”**


