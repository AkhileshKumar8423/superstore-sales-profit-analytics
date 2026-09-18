# Superstore Sales & Profit Analytics

## 📊 Project Overview

This project is an interactive Power BI dashboard built using the Superstore dataset.

The dashboard provides insights into:

- Sales Performance
- Profitability
- Orders
- Customers
- Categories & Sub-Categories
- Regional Performance
- Product Performance
- State-wise Sales

## 🎯 Business Questions

- What is the total sales and profit?
- Which category generates the highest sales?
- Which products are most profitable?
- Which regions perform best?
- Which states generate the highest sales?
- What is the overall profit margin?
- How are sales and profitability distributed across categories and regions?

## 📌 Key KPIs

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin %

## 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Data Visualization
- Data Analysis
- Business Intelligence
- Data Modeling

## 📐 Important DAX Measures

```DAX
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Total Orders = DISTINCTCOUNT(Superstore[Order ID])

Total Customers = DISTINCTCOUNT(Superstore[Customer ID])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

📈 Dashboard Features
KPI Cards
Sales Analysis
Profit Analysis
Category Analysis
Sub-Category Analysis
Regional Analysis
Product Analysis
State-wise Sales Map
Interactive Slicers

## 📸 Dashboard Preview

![Dashboard Preview](https://raw.githubusercontent.com/AkhileshKumar8423/superstore-sales-profit-analytics/main/dashboard-preview.jpg)
📂 Project File

The Power BI dashboard file is available in this repository:

Superstore Sales & Profit Analytics.pbix

👨‍💻 Author

Akhilesh Kumar

Data Analyst | Power BI | DAX | Data Visualization


