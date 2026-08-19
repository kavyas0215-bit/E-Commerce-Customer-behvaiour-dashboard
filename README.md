# 🛒 E-Commerce Customer Behaviour Analysis Dashboard

## 📌 Project Overview

**E-Commerce Customer Behaviour Analysis** is a data analytics project developed using **Excel, SQL, and Power BI** to analyze customer purchasing behaviour and e-commerce business performance.

E-commerce businesses generate large volumes of customer and transaction data. However, raw data alone does not provide meaningful insights into customer preferences, purchasing patterns, product performance, payment behaviour, and engagement.

This project transforms raw e-commerce data into **meaningful business insights** through data cleaning, SQL analysis, Excel-based data preparation, and an interactive **Power BI dashboard**.

The dashboard helps businesses understand customer behaviour, identify high-value customers, analyze product and payment trends, and support data-driven business and marketing decisions.

---

## 🎯 Problem Statement

E-commerce businesses need to understand how customers interact with products, payments, discounts, and purchases.

The absence of an effective analytical approach makes it difficult to:

* Identify high-value and frequent customers
* Understand customer purchasing behaviour
* Analyze product and category performance
* Evaluate payment preferences
* Understand customer demographics and locations
* Measure the impact of discounts and promotions
* Analyze customer engagement and purchasing patterns
* Identify potential customer retention or churn behaviour

This project addresses these challenges by developing an interactive analytics solution using **Excel, SQL, and Power BI**.

---

## 🎯 Project Objectives

1. Analyze **customer purchasing behaviour and trends**.
2. Identify **high-value and frequent customers**.
3. Analyze **sales and product-category performance**.
4. Understand **customer payment behaviour**.
5. Evaluate the impact of **discounts and promotions**.
6. Analyze customer preferences based on **location, payment method, and demographics**.
7. Identify factors associated with **customer retention/churn**, where applicable.
8. Create an **interactive Power BI dashboard** with important KPIs.
9. Provide **actionable business insights** for marketing and business decisions.

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                                           |
| ------------------- | ------------------------------------------------- |
| **Microsoft Excel** | Data cleaning, preprocessing and initial analysis |
| **MySQL**           | Data storage, querying and SQL analysis           |
| **Power BI**        | Interactive dashboard and visualization           |
| **DAX**             | Measures and KPI calculations                     |
| **Power Query**     | Data transformation and preparation               |

---

## 📊 Key Analysis Areas

### 👥 Customer Analysis

* Customer distribution
* Customer location analysis
* Customer purchasing behaviour
* High-value customers
* Frequent customers
* Customer segmentation

### 🛍️ Sales & Product Analysis

* Total sales
* Product/category performance
* Purchase trends
* Sales contribution by category
* Top-performing products/categories

### 💳 Payment Analysis

* Payment method distribution
* Payment value analysis
* Payment behaviour by customers
* Payment trends

### 📍 Location Analysis

* Customer city analysis
* Customer state analysis
* Geographic customer distribution

### 📈 Behaviour Analysis

* Purchase frequency
* Customer engagement
* Discount usage
* Promotion impact
* Retention/churn indicators where applicable

---

## 📌 Power BI Dashboard

The Power BI dashboard provides an interactive view of important business metrics and customer behaviour.

### 🔑 Key Performance Indicators

* **Total Customers**
* **Total Orders**
* **Total Payments**
* **Total Payment Value**
* **Average Payment Value**
* **Customer/Order-related KPIs**

### 📊 Visualizations

The dashboard includes interactive visualizations such as:

* Sales by Product Category
* Payment Type Distribution
* Customer State/City Analysis
* Customer Behaviour Trends
* Payment Value Analysis
* Customer and Order performance
* Interactive slicers for filtering the dashboard

---

## 🔄 Project Workflow

```text
Raw E-Commerce Dataset
        ↓
Data Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Excel Analysis
        ↓
MySQL Database
        ↓
SQL Queries & Analysis
        ↓
Power BI Data Connection
        ↓
Data Modelling
        ↓
DAX Measures
        ↓
Interactive Dashboard
        ↓
Business Insights
```

---

## 🧹 Data Preparation

The dataset was prepared before visualization by performing activities such as:

* Removing duplicate records
* Handling missing values
* Checking data types
* Cleaning inconsistent values
* Formatting date and numeric columns
* Validating customer and transaction data
* Preparing tables for analysis

---

## 🗄️ SQL Analysis

MySQL was used to store and analyze the e-commerce datasets.

SQL was used for:

* Aggregation
* Filtering
* Grouping
* Customer analysis
* Payment analysis
* Sales analysis
* Category-level analysis
* Identifying business trends

Example SQL concepts used:

```sql
SELECT
    customer_state,
    COUNT(*) AS customer_count
FROM customers
GROUP BY customer_state
ORDER BY customer_count DESC;
```

---

## 📈 Business Insights

The dashboard is designed to help answer questions such as:

* Which customer segments generate the most business value?
* Which product categories perform best?
* Which payment methods are most commonly used?
* Which locations have the highest customer concentration?
* What purchasing patterns can be observed?
* How do discounts influence purchasing behaviour?
* Which customers can be considered high-value?
* What factors may influence customer retention?

---

## 💡 Business Benefits

The analysis can help e-commerce businesses:

* Improve customer engagement
* Identify valuable customer segments
* Optimize marketing strategies
* Improve product/category performance
* Understand payment preferences
* Develop customer retention strategies
* Make data-driven business decisions
* Improve overall sales performance

---

## 📂 Project Structure

```text
E-Commerce-Customer-Behaviour-Analysis/
│
├── Dataset/
│   └── ecommerce_data.csv
│
├── Excel/
│   └── Ecommerce_Analysis.xlsx
│
├── SQL/
│   └── Ecommerce_Analysis.sql
│
├── PowerBI/
│   └── Ecommerce_Customer_Behaviour.pbix
│
├── Dashboard/
│   └── dashboard_screenshot.png
│
└── README.md
```

---

## 🚀 Future Enhancements

Future improvements can include:

* Customer churn prediction using Machine Learning
* Customer segmentation using clustering
* Sales forecasting
* Recommendation systems
* Advanced customer lifetime value analysis
* Automated dashboard refresh
* AI-powered business insights

---

## 👩‍💻 Skills Demonstrated

This project demonstrates practical skills in:

* **Microsoft Excel**
* **SQL / MySQL**
* **Power BI**
* **Power Query**
* **DAX**
* **Data Cleaning**
* **Data Analysis**
* **Data Visualization**
* **Business Intelligence**
* **Customer Behaviour Analysis**
* **Business Insight Generation**

---

## ⭐ Conclusion

The **E-Commerce Customer Behaviour Analysis Dashboard** converts raw e-commerce data into an interactive business intelligence solution.

By combining **Excel, SQL, and Power BI**, the project provides a structured approach to understanding customer behaviour, payment patterns, product performance, and business trends.

The final dashboard enables stakeholders to explore data interactively and make **data-driven decisions for improving customer engagement, sales performance, and retention strategies**.

---

## 📌 Project Type

**Data Analytics | Business Intelligence | Customer Behaviour Analysis**

**Tools:** Excel • MySQL • Power BI • DAX • Power Query

