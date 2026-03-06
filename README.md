# Superstore-Sales-Performance-Analysis
# 🛒 Superstore Sales Analysis (SQL + Power BI)

This project performs a complete **sales performance analysis** on a fictional **Superstore dataset** using **SQL Server** and **Power BI**. It demonstrates how retail data can be **cleaned, queried, analyzed, and visualized** to generate meaningful business insights and support strategic decision-making.

---

## 📌 Project Objective

The main objective of this project is to analyze **sales performance, customer behavior, product trends, and regional profitability**.

- **SQL Server** is used for **data cleaning, aggregation, KPI extraction, and analytical querying**
- **Power BI** is used for building an **interactive dashboard** to visualize trends and insights

---

## ⚙️ Tools & Technologies

- **SQL Server** — querying, aggregation, KPI extraction  
  👉 Add your SQL file link here

- **Power BI** — dashboard creation and visualization  
  👉 Add your dashboard screenshot or report link here

- **Excel** — raw dataset source  
  👉 Add your dataset file link here

---

## 📂 Dataset Overview

The dataset contains transactional retail sales data with the following fields:

| Column Name | Description |
|------------|-------------|
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping type (Standard Class, Second Class, etc.) |
| Customer ID | Unique ID for customers |
| Customer Name | Name of the customer |
| Segment | Customer type (Consumer, Corporate, Home Office) |
| Country / Region / City / State | Location-related fields |
| Product ID | Unique identifier for each product |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Name of the product |
| Sales | Total sales amount |
| Quantity | Quantity sold |
| Discount | Discount applied |
| Profit | Profit gained or lost |

---

## 🧠 SQL Questions Solved

### 🔹 Basic Analysis
- Total **sales, profit, and quantity**
- Unique values in **categories, segments, and ship modes**
- **Monthly and yearly sales summary**
- **Top-selling products** by sales and quantity
- Customers who ordered **only once**

### 🔹 Intermediate Analysis
- Sales and profit by **region, category, and segment**
- **Discount impact** on profitability
- Sales by **sub-category and product**
- **Profit margin %** by category
- **Shipping mode usage frequency**

### 🔹 Advanced Analysis
- **Monthly growth rate** using `LAG()` window function
- **Top profitable product by region** using `RANK()`
- **Bottom 10 loss-making products**
- Trend of **customer orders over time**
- **Customer segmentation** based on order count

---

## 📊 Key Insights

- **Technology** generated the highest overall sales
- **Office Supplies** showed the highest profit margins
- The **West region** outperformed other regions in both sales and profit
- Some products consistently resulted in **losses** and need review
- **Standard Class** is the most used ship mode, covering nearly **59% of total orders**
- Sales peak during **November and December**, indicating seasonal demand
- **Discounts above 30%** often lead to **negative profits**

---

## 📈 Power BI Dashboard Highlights

The dashboard includes:

- Sales and profit breakdown by **Category, Region, and Quarter**
- **Monthly sales trend** with quantity comparison
- Interactive filters for **Region, Year, and Segment**
- **Top and bottom performing products**
- **Sales vs Profit** relationship analysis
- **Donut charts and treemaps** for quick visual insights

---

## ✅ Conclusion

This project highlights how **SQL Server** and **Power BI** can be combined to transform raw retail data into valuable business insights. It showcases skills in **data cleaning, SQL analysis, KPI extraction, dashboarding, and business intelligence**.

---
