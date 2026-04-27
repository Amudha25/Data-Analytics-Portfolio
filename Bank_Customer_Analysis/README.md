# Corporate Banking Portfolio Analysis (Power BI)

## Overview
This project analyzes a **1-year anonymized corporate banking dataset (USD)** to identify key insights on **profitability, risk exposure, product mix, and wallet share opportunities**.  
The output is a **5-page interactive Power BI report** designed to support business decision-making and relationship manager prioritization.

---

## Tools Used
- Power BI (Data Model, DAX Measures, Dashboards)
- Power Query (Data Cleaning & Transformation)
- SQL (Data extraction / validation)
- Microsoft Excel (Initial data review and checks)

---

## Data Preparation (Power Query)
- Cleaned customer names by replacing irrelevant symbols/numbers with "Unknown"  
- Replaced NA values in numeric fields with nulls to ensure data consistency  
- Performed duplicate checks to ensure data quality  
- Created additional calculated columns for analysis  

---

## Data Model
- Single fact table (Sheet1)  
- Separate Measures table for DAX calculations  
- 25 DAX measures across Profitability, Risk, Product Mix, Wallet Share  

---

## Key Insights
- Revenue is highly concentrated in a small set of customers  
- Majority of customers have no lending exposure (~90%)  
- Significant deposit and lending opportunities remain untapped  
- High-risk exposure is concentrated in specific branches  
- Product usage strongly correlates with profitability  

---

## Customer Tier Strategy
| Tier | Label | Recommended Action |
|------|------|------------------|
| Tier 1 | 🟢 Grow | Deepen wallet share, cross-sell FX & Trade Finance |
| Tier 2 | 🔵 Develop | Introduce new products, increase deposit capture |
| Tier 3 | 🟡 Protect | Retain profit, manage credit cost |
| Tier 4 | 🔴 Review | Restructure or exit loss-making accounts |

---

## 📊 Dashboard Preview

### Overview Dashboard
[Executive Summary](./images/Executive_Summary.png)

### Profitability Analysis
[Profitability](./images/Profitability.png)

### Risk Analysis
[Risk Analysis](./images/Risk_Analysis.png)

### Product Mix 
[Product Mix](./images/Product_Mix.png)

### Wallet Share

[Wallet_Share](./images/Wallet_Share.png)



---

## Recommendations
- Focus on Tier 1 & Tier 2 customers for cross-sell opportunities  
- Improve deposit mobilization for high cash balance customers  
- Conduct credit risk review for high-risk segments  
- Increase FX and Trade Finance penetration  

---

## Files Included
- Power BI report (.pbix / .pbip)
- Supporting documentation (Customer Relationship Analysis.pptx)

---

## Author
**Amudha Devi**

🏦 Bank Customer Profitability Analysis Dashboard
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)
📌 Project Overview
This project is a 5-page interactive Power BI dashboard that analyses bank customer profitability across branches and customer tiers. It helps bank management and business teams understand which customers and branches are most profitable, assess financial risk, and evaluate product performance — enabling smarter, data-driven retention and growth strategies.
---
❓ Business Questions Answered
Which branches generate the highest gross and net profit?
How does profitability vary across different customer tiers?
Which customer segments are flagged as high or low profitability?
How is the product mix distributed across the customer base?
What is each customer segment's share of wallet?
Which customers or branches pose the greatest financial risk?
---
📊 Dashboard Pages
Page	Description
Executive Summary	High-level KPIs — Total Gross Profit, Net Profit, and customer count overview
Profitability	Deep-dive into profit by branch and customer tier; includes ROE analysis
Risk Assessment	Identifies customers and segments flagged by profitability risk indicators
Product Mix	Breakdown of product distribution across the customer base
Share of Wallet	Analyses what share of customer spending/assets the bank captures per segment
---
📈 Key Visuals Used
KPI Cards — Total Gross Profit, Total Net Profit, Total Customers
Clustered Bar & Column Charts — Profit and customer count by Branch and Customer Tier
Donut Chart — Customer distribution by tier
Scatter Chart — Net Profit by Profitability Flag, Gross Profit, and ROE
100% Stacked Column Chart — Product mix proportions across segments
Table — Detailed customer-level breakdown
Slicers — Filter by branch, customer tier, profitability flag, and product
---
🔍 Key Insights
Total Gross Profit and Net Profit vary significantly across branches, highlighting opportunities to replicate high-performing branch strategies
Customer Tier is a strong predictor of profitability — premium tiers contribute disproportionately to total profit
Profitability flagging (high/low/medium) enables the business team to prioritise retention efforts on at-risk but high-value customers
ROE analysis by profitability segment helps the bank assess where capital is being deployed most effectively
Share of Wallet view reveals segments where the bank has room to deepen relationships through cross-selling
---
🛠️ Tools & Technologies
Tool	Purpose
Power BI Desktop	Dashboard design, data modelling, visualisation
DAX	Custom measures — Total Gross Profit, Net Profit, ROE, Sum of Profit
Power Query	Data transformation and cleaning
Power BI Service	Publishing and sharing dashboards with stakeholders
---
📁 Repository Structure
```
Bank_Customer_Analysis/
├── data/
│   └── bank_customer_data.xlsx        # Source dataset
├── powerbi/
│   └── Amudha_Customer_Analysis.pbix  # Power BI dashboard file
├── screenshots/
│   ├── executive_summary.png
│   ├── profitability.png
│   ├── risk_assessment.png
│   ├── product_mix.png
│   └── share_of_wallet.png
└── README.md
```
---
▶️ How to Run This Project
Clone the repository
```bash
   git clone https://github.com/Amudha25/Data-Analytics-Portfolio.git
   cd "Data-Analytics-Portfolio/Bank_Customer_Analysis"
   ```
Open the Power BI file — Open `Amudha_Customer_Analysis.pbix` in Power BI Desktop (free download from Microsoft)
Refresh data — Update the data source path to your local copy of the dataset and click Refresh
Explore the dashboard — Navigate across the 5 pages using the page tabs at the bottom
> 💡 **Don't have Power BI Desktop?** Download it free from [Microsoft's website](https://powerbi.microsoft.com/desktop/)
---
👩‍💻 Author
Amudha Devi M.  
Data Analyst | Power BI Developer  
📧 amumahes@yahoo.com.sg  
🔗 LinkedIn | GitHub Portfolio
