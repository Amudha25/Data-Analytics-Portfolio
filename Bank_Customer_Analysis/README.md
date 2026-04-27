# Corporate Banking Portfolio Analysis (Power BI)

## Overview
This project is a 5-page interactive Power BI dashboard that analyses bank customer profitability across branches and customer tiers. It helps bank management and business teams understand which customers and branches are most profitable, assess financial risk, and evaluate product performance — enabling smarter, data-driven retention and growth strategies.

---
## Business Questions Answered

Which branches generate the highest gross and net profit?
How does profitability vary across different customer tiers?
Which customer segments are flagged as high or low profitability?
How is the product mix distributed across the customer base?
What is each customer segment's share of wallet?
Which customers or branches pose the greatest financial risk?

## Tools Used
- Power BI Desktop (Data Model, DAX Measures, Dashboards)
- Power Query (Data Cleaning & Transformation)
- SQL (Data extraction / validation)
- Microsoft Excel (Initial data review and checks)
- DAX (Custom measures — Total Gross Profit, Net Profit, ROE, Sum of Profit)
- Power BI Service (Publishing and sharing dashboards with stakeholders)

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
- Total Gross Profit and Net Profit vary significantly across branches, highlighting opportunities to replicate high-performing branch strategies
- Customer Tier is a strong predictor of profitability — premium tiers contribute disproportionately to total profit
- Profitability flagging (high/low/medium) enables the business team to prioritise retention efforts on at-risk but high-value customers
- ROE analysis by profitability segment helps the bank assess where capital is being deployed most effectively
- Share of Wallet view reveals segments where the bank has room to deepen relationships through cross-selling  

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
High-level KPIs — Total Gross Profit, Net Profit, and customer count overview
[Executive Summary](./images/Executive_Summary.png)

### Profitability Analysis
Deep-dive into profit by branch and customer tier; includes ROE analysis
[Profitability](./images/Profitability.png)

### Risk Analysis
Identifies customers and segments flagged by profitability risk indicators
[Risk Analysis](./images/Risk_Analysis.png)

### Product Mix 
Breakdown of product distribution across the customer base
[Product Mix](./images/Product_Mix.png)

### Wallet Share
Analyses what share of customer spending/assets the bank captures per segment
[Wallet_Share](./images/Wallet_Share.png)

## Key Visuals Used

KPI Cards — Total Gross Profit, Total Net Profit, Total Customers
Clustered Bar & Column Charts — Profit and customer count by Branch and Customer Tier
Donut Chart — Customer distribution by tier
Scatter Chart — Net Profit by Profitability Flag, Gross Profit, and ROE
100% Stacked Column Chart — Product mix proportions across segments
Table — Detailed customer-level breakdown
Slicers — Filter by branch, customer tier, profitability flag, and product

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

