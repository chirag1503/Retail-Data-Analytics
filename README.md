# Retail-Data-Analytics
“Exploratory Data Analysis and Dashboarding on Global Superstore dataset using Python, SQL, and Power BI.”
# 📊 Retail Superstore Data Analysis

This project analyzes the **Global Superstore dataset** containing **10,194 rows and 24 columns** of sales transactions.  
The goal is to demonstrate **data cleaning, SQL analysis, and interactive dashboards in Power BI** for business insights.


---

## 🔹 Dataset Overview
- **Rows:** 10,194  
- **Columns:** 24  
- **Key Columns:**  
  - `Order Date`, `Ship Date`, `Region`, `Category`, `Sub-Category`  
  - `Sales`, `Profit`, `Quantity`, `Discount`, `Customer ID`, `Segment`

The dataset represents **global sales transactions** across multiple product categories, customer segments, and shipping regions.

---

## 🔹 Workflow
1. **Data Cleaning (Python in Colab)**  
   - Removed duplicates & missing values  
   - Converted date fields into proper formats  
   - Standardized column names  
   - Exported cleaned dataset → `cleaned_superstore.csv`

2. **SQL Analysis**  
   - Connected dataset to SQLite in Colab  
   - Ran queries for:
     - Top-selling categories & sub-categories  
     - Customer lifetime value (CLV)  
     - Sales & profit by segment  
     - Discount impact on profitability  

3. **Power BI Dashboards (4 Pages)**  
   - Built interactive dashboards for business insights  

---

## 📊 Power BI Dashboards

### 1. **Executive Summary**
- KPIs: Total Sales, Total Profit, Total Orders, Avg. Discount %  
- Sales trend over time  
- Sales by  category  

### 2. **Product Performance**
- Top 10 Products by Sales & Profit  
- Sales distribution by Category & Sub-Category (Tree Map)  
- Identified best-selling vs least profitable products  

### 3. **Customer Insights**
- Top 10 Customers by Sales (CLV)  
- Customer spend distribution (Low/Medium/High spenders)  
- Customer segmentation by region & profit margin  

### 4. **Profitability & Trends**
- Profit Margin % (DAX measure)  
- Month-over-Month Growth % (DAX measure)  
- Sales vs Profit analysis   

---

## 🔹 Tools & Technologies
- **Python (Pandas, SQLite, SQLAlchemy)** → Data cleaning & SQL queries  
- **Power BI** → Interactive dashboards  
- **GitHub** → Project documentation & sharing  

---

## 📌 Key Insights
- Technology category contributes the **highest sales & profit**, while Furniture has **high sales but lower profit margins**.  
- Heavy discounts significantly reduce profit, especially in Office Supplies.  
- A small group of customers drive a large portion of total sales (80/20 rule).  
- Sales show seasonal trends, with spikes in Q4 (holiday season).  



