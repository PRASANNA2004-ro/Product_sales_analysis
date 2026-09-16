# Product Sales Analysis Dashboard

## 📊 Project Overview

The **Product Sales Analysis Dashboard** is a data analysis and visualization project created using **Microsoft Excel** and **Microsoft Power BI**.

The project analyzes product sales data to understand sales performance, profitability, orders, product performance, regional performance, and customer segments.

The Power BI dashboard provides an interactive way to explore the sales data using charts, KPI cards, and slicers.

---

## 🎯 Objectives

- Analyze overall product sales performance
- Track total net sales and total profit
- Analyze the number of orders and units sold
- Calculate average order value
- Analyze profit margin
- Compare sales across product categories
- Analyze regional sales performance
- Identify top-performing products
- Analyze monthly sales trends
- Compare product profitability
- Provide interactive filtering using slicers

---

## 🛠️ Tools Used

- **Microsoft Excel**
- **Microsoft Power BI**
- **GitHub**
- **DAX**

---

## 📁 Dataset

The project uses a product sales dataset containing **3,000 sales records**.

### Dataset Columns

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date of the order |
| Customer Name | Customer name |
| Customer Segment | Customer segment |
| Region | Sales region |
| State | Customer state |
| Sales Channel | Sales channel |
| Sales Rep | Sales representative |
| Product Category | Product category |
| Product Name | Product name |
| Unit Price | Price per unit |
| Quantity | Number of units sold |
| Discount % | Discount percentage |
| Gross Sales | Sales before discount |
| Discount Amount | Discount amount |
| Net Sales | Sales after discount |
| Unit Cost | Cost per unit |
| Total Cost | Total product cost |
| Profit | Profit generated |

---

## 📌 Dashboard Features

### KPI Cards

The dashboard contains six key performance indicators:

- **Total Net Sales**
- **Total Profit**
- **Total Orders**
- **Units Sold**
- **Average Order Value**
- **Profit Margin**

### Visualizations

The dashboard includes:

- **Net Sales by Category**
- **Net Sales by Region**
- **Top 10 Products by Net Sales**
- **Monthly Sales Trend**
- **Product Performance**
- **Profit by Category**

### Interactive Filters

Users can filter the dashboard using:

- Region
- Product Category
- Sales Channel
- Customer Segment
- State

---

## 📈 DAX Measures

The following DAX measures were used in the Power BI dashboard:

```DAX
Total Net Sales = SUM(SalesData[Net Sales])
Total Profit = SUM(SalesData[Profit])
Total Orders = DISTINCTCOUNT(SalesData[Order ID])
Units Sold = SUM(SalesData[Quantity])
Avg Order Value = DIVIDE([Total Net Sales], [Total Orders])
Profit Margin = DIVIDE([Total Profit], [Total Net Sales])
