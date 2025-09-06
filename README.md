# Finance-Analytics-Dashboard-in-Power-BI-From-Data-Cleaning-to-Business-Insights
# Finance Analytics Dashboard in Power BI

I recently worked on a **Finance Dataset Project in Power BI**, where the objective was to transform raw data into meaningful insights for decision-making.  
This project helped me apply the complete BI lifecycle – from **data cleaning, modeling, measure creation to advanced visualization.**

---

## 🎯 Objective
To analyze **Sales, Profit, Product Performance, Customer Segments, and Geographic Trends** and present them through an interactive **multi-page dashboard** for business decision-makers.

---

## 🛠️ Process

### 1. Data Cleaning (Power Query)
- Removed duplicate rows  
- Standardized column names (`Sales`, `Profit`, `Quantity`, `Discount Band`, `Segment`)  
- Ensured correct data types (`Date → Date`, `Sales/Profit → Decimal`)  
- Derived a clean **Date column** for Time Series Analysis  

### 2. Added Columns
- `Year` & `Month` (from Date) for trend analysis  
- `Profit Margin = Profit / Sales` (calculated measure)  

### 3. Key Measures (DAX)
```DAX
Total Sales = SUM(Sales)  
Total Profit = SUM(Profit)  
Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))

 💬 Would love to hear your thoughts – What’s your favorite chart when analyzing business performance?
