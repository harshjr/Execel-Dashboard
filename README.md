# Execel-Dashboard
# 📊 BlinkIT Grocery Data Excel Dashboard

## 🔶 Overview

This project presents an interactive and analytical Excel Dashboard built using real-world grocery order data from **BlinkIT**. The dashboard provides deep insights into sales trends, category performance, top products, and regional analysis — helping stakeholders make data-driven decisions in a grocery delivery business context.

---

## 🎯 Objectives

- Analyze and visualize BlinkIT grocery sales data.
- Track key performance indicators (KPIs) such as revenue, orders, and top products.
- Identify customer purchase patterns and category-wise trends.
- Create a user-friendly dashboard with dynamic filters (slicers) and summary visuals.

---

## 📂 Dataset Description

The dataset includes columns such as:

- `Order ID`
- `Product Name`
- `Category`
- `Quantity`
- `Price`
- `Order Date`
- `Region`

Additional columns derived:
- `Total Price = Quantity × Price`
- `Month` and `Year` extracted from `Order Date`

---

## 🧱 Methodology

### ✅ Step 1: Data Cleaning
- Removed nulls and duplicates.
- Standardized date formats and calculated `Total Price`.

### ✅ Step 2: Pivot Tables Created
- Sales by Category
- Monthly Sales Trend
- Top Products by Revenue
- Regional Sales
- Order Count per Month

### ✅ Step 3: Visual Elements Used
| Type         | Description                           |
|--------------|---------------------------------------|
| Column Chart | Monthly sales comparisons             |
| Line Chart   | Sales and orders trends over time     |
| Pie Chart    | Category-wise contribution            |
| Bar Chart    | Top-selling products                  |
| KPI Cards    | Total Revenue, Orders, Avg Basket Size|

---

## 📊 Dashboard Features

- **Dynamic KPIs** showing revenue, order count, top category/product, etc.
- **Slicers** for filtering data by Category, Region, and Month.
- **Interactive Charts** linked to pivot tables and slicers.
- **Clean layout** designed for stakeholder readability and presentation.

---

## 📌 Key Insights

- Categories like **Beverages** and **Snacks** are top contributors.
- **Top 10 products** drive a major portion of revenue.
- Certain **months/regions** see spikes in order volume.
- **Sales trend line** reveals seasonal fluctuations.

---

## 📘 Tools Used

- Microsoft Excel
  - Pivot Tables
  - Charts & Graphs
  - Slicers
  - Conditional Formatting
  - Dashboard layout techniques
- Excel Formulas: `SUMIFS()`, `COUNTIFS()`, `AVERAGE()`, `TEXT()`, etc.

---

## 📁 Files Included

- `BlinkIT Grocery Dashboard.xlsx` — Main dashboard file
- `README.md` — Project documentation
- *(Optional)*: `Presentation.pptx` for viva or showcase

---

## ✅ Future Enhancements

- Add **customer segmentation** and retention analysis.
- Use **forecasting tools** (like Excel trendlines or Power BI).
- Incorporate **inventory or supply chain data** for broader analysis.

---

