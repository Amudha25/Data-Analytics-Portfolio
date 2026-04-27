🏠 HDB Resale Market Analysis Dashboard
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

📌 Project Overview
This project analyses 150,000+ HDB resale flat transactions in Singapore to uncover pricing trends, demand patterns, and market drivers. The data is hosted on Azure SQL Database and visualised through an interactive Power BI dashboard designed for homebuyers, property analysts, and researchers.
---
❓ Business Questions Answered
- Which towns have the highest and lowest resale flat prices?
- How does flat type (3-room, 4-room, 5-room, etc.) affect resale value?
- What is the impact of remaining lease years on resale price?
- Which areas have seen the highest price growth over time?
- Where is demand (transaction volume) the highest?
---
🔍 Key Insights
- Mature estates (Bishan, Queenstown, Toa Payoh) command a 15–25% price premium over non-mature towns
- 5-room flats in Bishan consistently achieve the highest median resale prices across all flat types
- Flats with less than 60 years of remaining lease show a measurable price discount, especially in resale-heavy towns
- Transaction volumes peaked in Q2–Q3, indicating seasonal demand patterns useful for timing a purchase or sale
---
🛠️ Tools & Technologies
Tool	Purpose
- Azure SQL Database	Cloud hosting of resale transaction datasets
- SQL (T-SQL)	      Data extraction, filtering, and aggregation queries
- Power BI Desktop	Data modelling, DAX measures, dashboard design
- Power Query	      Data cleaning and transformation
- Power BI Service	Dashboard publishing and sharing
---
📊 Dashboard Features
- KPI Cards — Median price, total transactions, average price per sqm
- Choropleth / Bar Charts — Price comparison by town and flat type
- Line Chart — Resale price trend over time (monthly/yearly)
- Scatter Plot — Remaining lease vs. resale price relationship
- Slicers — Filter by town, flat type, storey range, and year
- Drillthrough — Click any town to see flat-level breakdown
---
📁 Repository Structure
```
HDB_Resale_Price_Dashboard/
├── data/
│   └── hdb_resale_data.csv         # Source dataset
├── sql/
│   └── hdb_queries.sql             # SQL queries for extraction & analysis
├── powerbi/
│   └── HDB_Resale_Dashboard.pbix   # Power BI dashboard file
├── screenshots/
│   └── dashboard_overview.png      # Dashboard preview images
└── README.md
```
---
▶️ How to Run This Project
Clone the repository
```bash
   git clone https://github.com/Amudha25/Data-Analytics-Portfolio.git
   ```
- Set up the database — Import `data/hdb_resale_data.csv` into Azure SQL Database or a local SQL Server instance
- Update connection — Open `HDB_Resale_Dashboard.pbix` in Power BI Desktop and update the data source connection string
- Refresh data — Click Refresh in Power BI Desktop to load the latest data
- Explore the dashboard — Use slicers to filter by town, flat type, and year
---
📂 Data Source
HDB Resale Flat Prices — data.gov.sg (Singapore Open Data)
---
👩‍💻 Author
Amudha Devi M.  
Data Analyst | Power BI Developer  
📧 amumahes@yahoo.com.sg  
🔗 LinkedIn | GitHub Portfolio


