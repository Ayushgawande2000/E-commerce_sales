Dashboard page:-

1.Sales Overview

KPI Cards:

Total Sales

Total Profit

Total Orders

Line Chart → Monthly Sales Trend

Bar Chart → Sales by Region

2.Customer \& Product Insights

Top 10 Customers (Bar Chart)

Sales by Category \& Sub-category

Top Products

3.Profit \& Discount Analysis

Scatter Plot:

X → Discount

Y → Profit

Tree Map → Profit by Category

4.Payment \& Order Analysis

Pie Chart → Payment Mode

Orders by City / State

**DAX MEASURE:-**

Total Sales = SUM(Sales\[Sales])

Total Profit = SUM(Sales\[Profit])

Profit Margin % = DIVIDE(\[Total Profit],\[Total Sales])\*100

AOV = DIVIDE(\[Total Sales], DISTINCTCOUNT(Sales\[Order ID]))

Month Year = FORMAT(Sales\[Order Date],"MMM YYYY")

**GITHUB STRUCTURE:-**

**📁 PowerBI-Ecommerce-Analysis**

&#x20;**┣ 📄 Ecommerce\_Dashboard.pbix**

&#x20;**┣ 📄 Dataset.csv**

&#x20;**┣ 📄 README.md**

&#x20;**┗ 📄 Questions.md**



