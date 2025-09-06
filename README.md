# Finance-Analytics-Dashboard-in-Power-BI-From-Data-Cleaning-to-Business-Insights
I recently worked on a Finance Dataset project in Power BI, where the objective was to transform raw data into meaningful insights for decision-making. This project helped me apply the complete BI lifecycle – from data cleaning, modeling, and measure creation to advanced visualization.
🎯 Objective
To analyze Sales, Profit, Product Performance, Customer Segments, and Geographic Trends and present them through an interactive multi-page dashboard for business decision-makers.
 Process
1. Data Cleaning (Power Query)
Removed duplicate rows
Standardized column names (e.g., Sales, Profit, Quantity, Discount Band, Segment)
Ensured correct data types (Date → Date, Sales/Profit → Decimal)
Derived a clean Date column for Time Series Analysis
2. Added Columns
Year & Month (from Date) for trend analysis
Profit Margin = Profit / Sales (calculated measure)
3. Key Measures (DAX)
Total Sales = SUM(Sales)
Total Profit = SUM(Profit)
Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))
KPI Targets (e.g., Profit Margin Target = 20%)
📊 Visualizations & Insights
I used different chart types to answer key business questions:
Scatter Chart (Sales vs Profit by Product) → Identify High Sales but Low Profit products ⚠️
Column Chart (Revenue vs Profit) → Gap between Sales and Profit across categories
Map Chart (Country-wise Sales) → Business performance by geography 🌍
Stacked Bar (Segment vs Profit) → Which customer type (Government, Small Business, Midmarket) is most profitable
Treemap (Product vs Sales & Profit) → Top & low-performing products
Line Chart (Sales & Profit over Time) → Growth & seasonality trends 📈
Gauge Chart (Profit Margin vs Target) → Financial health against company goals
📑 Dashboard Layout (4 Pages)
Executive Summary
KPIs: Total Sales, Profit, Profit Margin
Sales vs Profit (gap analysis)
Country-wise Sales overview
Customer & Market Analysis
Segment profitability
Top 10 countries by Sales
Product performance (Treemap)
Time Analysis
Monthly/Yearly Sales & Profit Trends
Seasonal insights
Effect of Discounts on Sales & Profit
Financial Insights
Profit Margin vs Target (Gauge KPI)
Category-wise Profit Margin
Sales vs Profit Scatter (Product-level analysis)
🌟 Outcome
This project highlights how raw financial data can be transformed into a professional dashboard that empowers decision-makers to:
Identify loss-making products despite high sales
Plan expansion strategy based on country/region
Understand customer segment profitability
Track overall financial health
📌 Key Skills Used: Power BI, Power Query (ETL), DAX (Calculated Measures), Data Modeling, Data Visualization
👉 Excited to share this as part of my portfolio!
 💬 Would love to hear your thoughts – What’s your favorite chart when analyzing business performance?
