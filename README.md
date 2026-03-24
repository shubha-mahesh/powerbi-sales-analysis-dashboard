# powerbi-sales-analysis-dashboard
This project analyzes sales and profit data using Power BI to identify key business insights such as top-performing categories, underperforming regions, and loss-making products.
The goal is to support data-driven decision-making by highlighting trends and inefficiencies.

Dataset
Dataset: Superstore Sales Dataset

The dataset contains information on:
- Sales
- Profit
- Discounts
- Categories
- Regions
- Customers
- Order Dates

Key KPIs
- Total Sales = SUM(Sales)
- Total Profit = SUM(Profit)
- Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))
- Previous Month Sales = 
CALCULATE([Total Sales], DATEADD('Table'[Order Date], -1, MONTH))
- MoM Growth = 
DIVIDE([Total Sales] - [Previous Month Sales], [Previous Month Sales])

🔹 Key Business Questions
- Which category generates the highest profit?
- Which region is underperforming?
- How do sales change over time?
- Which products are loss-making?
- Who are the top profitable customers?
🔹 Insights (THIS IS YOUR WEAPON 🔥)
- Technology category contributes the highest profit.
- Central region shows the lowest profitability.
- Several products generate negative profit, indicating pricing or discount issues.
- High sales do not always result in high profit.
- A small set of customers contributes significantly to profit.



🔹 Tools Used
- Power BI
- DAX (Data Analysis Expressions)
- Data Visualization
