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

Key Business Questions
- Which category generates the highest profit?
- Which region is underperforming?
- How do sales change over time?
- Which products are loss-making?
- Who are the top profitable customers?


Insights 
- Technology category drives the highest profit.
- Central region underperforms compared to others.
- Several products generate significant losses, with a few contributing disproportionately.
- Some high-sales products are loss-making, indicating pricing or discount inefficiencies.
- Customer profitability varies significantly, with some customers contributing negatively.
- Sales peak during mid-year (july-Q3), suggesting seasonality.


Business Impact

- Identified key loss drivers to improve profitability.
- Highlighted high-value customers for retention strategies.
- Provided insights into seasonal sales trends for better planning.

🔹 Tools Used
- Power BI
- DAX (Data Analysis Expressions)
- Data Visualization
