# DAX Measures

## Total Sales
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Total Orders = DISTINCTCOUNT(Superstore[Order ID])

Total Customers = DISTINCTCOUNT(Superstore[Customer ID])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Recommended Formatting
Sales → Currency
Profit → Currency
Orders → Whole Number
Customers → Whole Number
Profit Margin % → Percentage

