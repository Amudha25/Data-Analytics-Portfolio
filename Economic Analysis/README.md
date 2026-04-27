🛒 ##** E-Commerce Sales & Customer Behaviour Dashboard**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

📌 Project Overview
- This project analyses an e-commerce company's sales data to understand customer behaviour, sales performance, and profitability across product categories and regions. The Power BI dashboard helps business teams identify growth opportunities, optimise product strategy, and improve marketing targeting.
---
❓ Business Questions Answered
- Which product categories generate the most revenue and profit?
- Who are the most valuable customer segments?
- Are there seasonal patterns in sales that can inform promotions?
- Which regions are underperforming and why?
- What is the relationship between discount levels and profitability?
---
🔍 Key Insights
- Technology is the highest revenue category, but Office Supplies has the highest profit margin percentage
- The top 20% of customers account for over 60% of total revenue — strong case for loyalty programmes
- Q4 (Oct–Dec) consistently generates 35%+ of annual revenue due to year-end demand spikes
- Heavy discounting (>30%) correlates with negative profit margins in the Furniture category
- The Central region shows the lowest profit margin despite above-average sales volume, suggesting high fulfilment costs
---
🛠️ Tools & Technologies
Tool	Purpose
- Microsoft Excel	Data cleaning, pivot tables, and initial exploration
- Power BI Desktop	Data modelling, DAX measures, interactive dashboards
- Power Query	Data transformation and column standardisation
- DAX	Custom KPI measures (profit margin %, YoY growth, customer LTV)
---
📊 Dashboard Features
- Executive Summary Page — Total revenue, profit, orders, and YoY growth KPIs
- Sales by Category — Bar chart breakdown of revenue and profit by product category
- Customer Segmentation — RFM (Recency, Frequency, Monetary) analysis by segment
- Regional Performance Map — Geographic heatmap of sales and profit by region/state
- Time-Series Analysis — Monthly sales trend with forecast overlay
- Discount vs. Profit Analysis — Scatter plot highlighting unprofitable discount bands
- Slicers — Filter by year, category, region, and customer segment
---
📁 Repository Structure
```
Market Analysis/
├── data/
│   └── ecommerce_sales_data.xlsx      # Cleaned source dataset
├── powerbi/
│   └── Ecommerce_Dashboard.pbix       # Power BI file
├── excel/
│   └── EDA_Pivot_Analysis.xlsx        # Excel exploratory analysis
├── screenshots/
│   ├── executive_summary.png
│   ├── customer_segments.png
│   └── regional_performance.png
└── README.md
```
---
▶️ How to Run This Project
Clone the repository
```bash
   git clone https://github.com/Amudha25/Data-Analytics-Portfolio.git
   cd "Data-Analytics-Portfolio/Market Analysis"
   ```
- Open Excel file — Review the raw data and pivot analysis in `EDA_Pivot_Analysis.xlsx`
- Open Power BI file — Open `Ecommerce_Dashboard.pbix` in Power BI Desktop
- Refresh data source — Update the file path to your local copy of the Excel data and click Refresh
- Explore the dashboard — Use slicers to filter by year, category, and region
---
---
👩‍💻 Author
Amudha Devi M.  
Data Analyst | Power BI Developer  
📧 amumahes@yahoo.com.sg  
🔗 LinkedIn | GitHub Portfolio
