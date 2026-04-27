🛒 **BI for E-Commerce Operations — Market & Sales Analysis Dashboard**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

📌 Project Overview
- This project is a 5-page interactive Power BI dashboard built for an e-commerce business to analyse sales performance, customer behaviour, product profitability, and margin trends. The dashboard enables business teams to monitor revenue growth, understand their customer base, and identify top-performing products — all in one place.
---
❓ Business Questions Answered
- What is the overall sales and profit performance year on year?
- Who are our customers — by age, income, gender, and country?
- Which products and categories drive the most sales and profit?
- How does average order value vary across customer age and income groups?
- What is the relationship between shipping cost and profit margin?
- Which customer segments generate the highest revenue?
---
📊 Dashboard Pages
Page	Description
- Overview	High-level KPIs — Total Revenue, Net Profit, Gross Margin %, Total Quantity, and Yearly Sales trend
- Customer Details	Customer segmentation by age group, income bucket, gender, and country; top customers by revenue
- Purchase Analysis	Average order value by age and income; yearly net profit trend; sales instances
- Product Tooltips	Top 5 products by sales and profit; category-level breakdown
- Margin Tooltips	Shipping cost vs. profit margin analysis; margin group distribution
---
📈 Key Visuals Used
- KPI Cards — Total Revenue, Net Profit, Gross Margin %, Total Quantity, Average Income, Average Age
- Bar Charts — Top 5 Products by Sales and Profit; Customers by Country and Income Bucket
- Donut Chart — Customer distribution by Gender and Age Bucket
- Area Chart — Yearly Total Sales and Net Profit by Year trends
- Scatter Chart — Shipping Cost vs. Profit Margin relationship
- Pivot Table — Detailed product and customer breakdown
- Page Navigator & Action Buttons — Seamless navigation across dashboard pages
- Slicers — Filter by Category, Country, Gender, Age Bucket, Income Bucket, and Date
---
🔍 Key Insights
- Yearly Total Sales trend reveals seasonal peaks and growth patterns useful for planning promotions and inventory
- Top 5 Products by Profit vs. Top 5 by Sales comparison highlights products with high volume but low margins — flagging pricing optimisation opportunities
- Average Order Value by Income shows that higher income brackets spend significantly more per order, supporting targeted upselling strategies
- Shipping Cost vs. Profit Margin scatter reveals that high shipping costs are compressing margins in specific product categories
- Customer segmentation by Age Bucket and Income Bucket identifies the most valuable demographic groups for marketing focus
- Public Holiday calendar integration allows correlation of sales spikes with holiday periods
---
🛠️ Tools & Technologies
Tool	Purpose
- Power BI Desktop	Dashboard design, data modelling, visualisations
- DAX	Custom measures — Net Profit, Gross Margin %, Average Order Value, Total Revenue
- Power Query	Data transformation and cleaning
- Excel	Source data preparation
- Power BI Service	Publishing and sharing dashboards
---
🗂️ Data Tables Used
Table	Description
- `customer`	Customer demographics — Name, Gender, Age, Income, Country
- `purchase`	Transaction data — Order ID, Customer ID, Product, Quantity, Sales Amount, Shipping Cost, Order Date
- `Item Category Map`	Product to category mapping
- `Calender`	Date table for time intelligence calculations
- `Public Holiday`	Singapore public holiday reference for sales trend analysis
---
📁 Repository Structure
```
Market Analysis/
├── data/
│   └── ecommerce_data.xlsx                              # Source dataset
├── powerbi/
│   └── Market_Analysis_BI_for_E-Commerce_Operations.pbix  # Power BI dashboard file
├── screenshots/
│   ├── overview.png
│   ├── customer_details.png
│   ├── purchase_analysis.png
│   ├── product_tooltips.png
│   └── margin_tooltips.png
└── README.md
```
---
▶️ How to Run This Project
Clone the repository
```bash
   git clone https://github.com/Amudha25/Data-Analytics-Portfolio.git
   cd "Data-Analytics-Portfolio/Market Analysis"
   ```
Open the Power BI file — Open `Market_Analysis_BI_for_E-Commerce_Operations.pbix` in Power BI Desktop
Refresh data — Update the data source path to your local copy of the Excel file and click Refresh
Explore — Use the page navigator buttons and slicers to filter by category, country, age group, and more
> 💡 **Don't have Power BI Desktop?** Download it free from [Microsoft's website](https://powerbi.microsoft.com/desktop/)
---
👩‍💻 Author
Amudha Devi M.  
Data Analyst | Power BI Developer  
📧 amumahes@yahoo.com.sg  
🔗 LinkedIn | GitHub Portfolio
