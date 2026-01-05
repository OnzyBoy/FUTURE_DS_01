# FUTURE_DS_01
# Online Retail Sales Analytics Dashboard (Power BI)

## 📊 Project Overview
This project focuses on analyzing **e-commerce sales data** to uncover insights that support data-driven business decisions. Using **Power BI**, an interactive dashboard was developed to identify **sales trends**, **best-selling products**, and **high-revenue countries**.

The dashboard is designed for business users to quickly understand performance metrics and explore data through interactive filters.

---

## 🎯 Business Objectives
The analysis aims to answer the following key questions:
- Which products generate the highest revenue?
- How do sales trends vary by month and year?
- Which countries contribute the most to total revenue?
- What are the overall sales performance metrics?

---

## 📁 Dataset
- **Source:** Kaggle - [Online Retail II Data Set from ML Repository](https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository/data)
- **Format:** Excel
- **Time Period:** 2009 – 2011
- **Key Fields:**  
  `Invoice`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `Price`, `CustomerID`, `Country`

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Microsoft Excel**
- **DAX (Data Analysis Expressions)**

---

## 🧹 Data Preparation & Cleaning
The following steps were performed in **Power Query**:
1. Combined data from two years (2009–2010 and 2010–2011)
2. Removed invalid transactions:
   - Quantity ≤ 0
   - Price ≤ 0
3. Ensured correct data types (especially Date/Time)
4. Created time-based columns:
   - Year
   - Month Number
   - Month Name
5. Created a calculated **Revenue** column:
   - [Quantity] * [Price]

---

## 📐 Key DAX Measures
The following measures were created to support analysis:
- **Total Revenue**
- **Total Quantity Sold**
- **Total Orders (Distinct Invoice Count)**
- **Average Order Value** *(optional KPI)*

---

## 📈 Dashboard Features
The Power BI dashboard includes:
- **Monthly Revenue Trend** (Year-over-Year comparison)
- **Top 10 Best-Selling Products by Revenue**
- **Total Revenue by Country (Geographic Analysis)**
- **KPI Cards** for quick performance overview
- **Interactive Slicers** for Year, Month, and Country

---

## 💡 Key Insights
- Sales peak towards the end of the year, especially in **November**
- A small number of products contribute a significant portion of total revenue
- European countries generate the highest sales revenue
- Seasonal trends strongly influence purchasing behavior

---

## 📂 Repository Contents
- `SalesAnalysis.pbix` – Power BI dashboard file
- `README.md` – Project documentation

---

## 🚀 Future Improvements
- Add customer segmentation analysis
- Incorporate profit and cost metrics
- Build additional drill-through pages
- Automate data refresh using Power BI Service

---

## 👤 Author
**Aristo Ayako**  
Data Analytics & Data Science Intern  


