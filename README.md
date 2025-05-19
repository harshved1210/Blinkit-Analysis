# 🛒 Blinkit Data Analysis Project

## 📌 Overview

This project provides a comprehensive analysis of Blinkit's data, focusing on customer behavior, sales performance, and operational insights. It spans from requirement gathering to final dashboard/report development using tools such as Power BI, Excel, and Python (if applicable).

---

## 📊 Business Objectives

- Understand customer ordering behavior and patterns.
- Analyze sales trends and product popularity.
- Identify high-performing and underperforming categories.
- Provide actionable insights through interactive dashboards.

---

## ✅ Project Workflow

### 1. 📋 Requirement Gathering / Business Requirements

- Stakeholder meetings were conducted to understand the key KPIs and business goals.
- Defined critical questions to be answered:
  - What are the most popular products and categories?
  - What are the peak order times and days?
  - Which locations have the highest/lowest sales?

---

### 2. 🧾 Data Walkthrough

- Explored datasets for:
  - Orders
  - Customers
  - Products
  - Categories
  - Delivery Information
- Assessed column meanings, relationships, and data types.

---

### 3. 📥 Data Collection

- Datasets were collected from Blinkit's backend systems or publicly available sources.
- Data sources used:
  - CSV/Excel files
  - APIs (if applicable)

---

### 4. 🧹 Data Cleaning / Quality Check

- Checked for:
  - Null/missing values
  - Duplicates
  - Inconsistent formats
- Handled missing data using appropriate techniques (e.g., imputation, removal).
- Ensured standardization of units, date formats, and category labels.

---

### 5. 🗃️ Data Modeling

- Established relationships between tables (star schema).
- Defined primary and foreign keys.
- Optimized table structures for reporting in Power BI.

---

### 6. ⚙️ Data Processing

- Transformed raw data using Power Query/Python:
  - Extracted year, month, weekday from dates.
  - Calculated order durations.
  - Created new metrics and normalized data.

---

### 7. 🧮 DAX Calculations

Created key DAX measures including:

- Total Sales  
- Average Order Value  
- Number of Orders  
- Sales by Category  
- Top Products by Revenue  
- Month-over-Month Growth  

---

### 8. 🧩 Dashboard Lay Outing

- Designed dashboard layout with user-friendly navigation.
- Used consistent color schemes and font styles.
- Sections:
  - Sales Overview
  - Customer Insights
  - Product Analysis
  - Time-Based Trends

---

### 9. 📈 Charts Development and Formatting

Developed and formatted charts including:

- Bar Charts (Top Products, Categories)
- Line Charts (Sales Trends Over Time)
- Pie Charts (Category Share)
- Maps (Regional Sales)
- KPIs (Total Sales, Orders, Avg Value)

---

### 10. 📊 Dashboard / Reports Development

- Created interactive dashboards in Power BI.
- Included slicers for dynamic filtering (by city, product, time).
- Published and shared reports with stakeholders.

---

## 🛠️ Tools Used

- Power BI
- MS Excel
- Python (Pandas, NumPy) – *(optional, if preprocessing done in Python)*
- SQL – *(optional, if data extracted from databases)*

---

## 📎 Project Folder Structure

```bash
Blinkit-Analysis/
│
├── data/
│   ├── orders.csv
│   ├── customers.csv
│   └── products.csv
│
├── scripts/
│   └── data_cleaning.ipynb
│
├── dashboards/
│   └── blinkit_dashboard.pbix
│
├── reports/
│   └── business_insights.pdf
│
└── README.md
