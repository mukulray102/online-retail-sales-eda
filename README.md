# 🛒 Online Retail Sales – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of the **Online Retail dataset**, which contains transactional data from an online retail company.  
The analysis focuses on uncovering **sales trends, customer behavior, product performance, and business insights** using Python.

The project is designed as a **portfolio project** .

---

## 🎯 Project Objectives

- Load and explore the Online Retail dataset
- Clean and preprocess raw transactional data
- Explore the basic statistics of the dataset
- Data visualization to gain insights
- Detect outliers and anomalies
- Analyze sales trends over time
- Understand customer purchasing behavior
- Identify top-selling products and countries
- Summarize actionable business insights

---

## 🗂 Dataset Description

**Source:** UCI Machine Learning Repository – Online Retail Dataset  
**Time Period:** December 2010 – December 2011  

### Key Columns

| Column Name   | Description |
|--------------|-------------|
| InvoiceNo    | Unique invoice number |
| StockCode    | Product code |
| Description  | Product description |
| Quantity     | Quantity of items purchased |
| InvoiceDate  | Date and time of transaction |
| UnitPrice    | Price per unit |
| CustomerID   | Unique customer identifier |
| Country      | Customer country |

---

## 🧹 Data Cleaning & Preparation

The following steps were performed:

- Removed rows with missing `CustomerID`
- Excluded cancelled or returned transactions (`Quantity ≤ 0`)
- Removed invalid pricing records (`UnitPrice ≤ 0`)
- Created a new feature:
  - **Sales = Quantity × UnitPrice**
- Converted `InvoiceDate` into:
  - Date
  - Month
  - Days (Day of week)

---

## 📊 Exploratory Data Analysis

### 1. Descriptive Statistics
- Measures of central tendency and dispersion
- Distribution analysis of Quantity, UnitPrice, and Sales

### 2. Sales Trend Analysis
- Monthly sales trends
- Day-of-week sales patterns
- Identification of peak sales periods

### 3. Product Analysis
- Top-selling products by:
  - Quantity
- Top-selling countries by:
  - Quantity

### 4. Country-Level Analysis
- Top-selling countries by:
  - Quantity
- Identification of dominant markets

### 5. Outlier & Anomaly Detection
- High-value invoices
- Extreme quantities and prices
- Discussion of their potential business impact

---

## 📈 Key Insights
- Sales are highly right-skewed, indicating a small number of high-value transactions.
- The data is not enough for monthly seasonality check because of short-lenght just 1 year and one month.
- The highest transaction occur On November, 2011 .
- Sales are highest on Thursday .
- Product "PACK OF 72 RETROSPOT CAKE CASES" has highest sales volume .
- UK dominates sales volume compared to other countries .
- Outliers reflect bulk orders and should be treated cautiously .

---

## 🛠 Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- plotly

---

## 📁 Repository Structure
```
online-retail-sales-eda/
│
├── data/
│ └── Online Retail.xlsx
│
├── notebooks/
│ └── Online Retail EDA.ipynb
│
├── README.md
```

---

## 👤 Author

**Mukul Chandra Ray**  
Aspiring Data Analyst / Data Scientist  
Background: Statistics & Data Analytics  

📫 *Feel free to connect or provide feedback.*

---

## ⭐ Acknowledgement

If you find this project useful, consider giving it a **star ⭐** to support my work.
