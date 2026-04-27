# 🌍 Global Performance Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![CSV](https://img.shields.io/badge/Data-CSV-green?style=for-the-badge)

## 📌 Project Overview

This project is a **6-dashboard interactive Tableau workbook** that analyses global country-level performance across **5 key dimensions** — Economic, Social, Environmental, Technological, and Military. Built using a comprehensive country comparison dataset covering 36 indicators, the dashboards allow researchers, policy analysts, and business teams to compare nations, track trends over time, and derive actionable insights across multiple domains.

---

## ❓ Business Questions Answered

- Which countries have the highest GDP and GDP per Capita, and how have they trended over time?
- How do inflation and unemployment rates compare across nations?
- Which countries lead or lag in renewable energy adoption and CO2 emissions?
- How does life expectancy, literacy rate, and healthcare expenditure vary globally?
- Which nations have the highest military expenditure and active personnel?
- How does internet penetration and smartphone adoption differ across countries?
- What is the relationship between economic growth and social or environmental outcomes?

---

## 📊 Dashboard Pages

| Dashboard | Key Metrics Covered |
|-----------|-------------------|
| **Home** | Navigation hub — entry point to all 5 indicator dashboards |
| **Economic** | GDP (Trillions USD), GDP per Capita, Inflation Rate (%), Unemployment Rate (%) |
| **Social** | Literacy Rate, Healthcare Expenditure per Capita, Life Expectancy, Population Growth Rate |
| **Environmental** | CO2 Emissions, Renewable Energy Share (%), Forest Coverage (%), Energy Consumption (TWh) |
| **Technological** | Internet Penetration (%), Smartphone Adoption (%) |
| **Military** | Military Expenditure (Billion USD), Active Military Personnel |

---

## 📈 Key Visuals Used

- **KPI Cards** — Latest value for each indicator per selected country
- **Bar Charts** — Country-level ranking for all indicators
- **Trend Line Charts** — "Trend over the years" for GDP, GDP per Capita, Inflation, Unemployment, CO2, Forest Coverage, Renewable Energy, Internet Penetration, Smartphone Adoption, Military Expenditure, Active Personnel
- **Map** — Geographic view of indicator values across countries
- **Parameter Control** — Dynamic Indicator Group selector (Economic / Social / Environmental / Technology / Military) to switch dashboard context
- **Filters** — Country and Year filters across all dashboards

---

## 🔍 Key Insights

- **Economic:** GDP trends reveal significant divergence between high-income and developing nations, with GDP per Capita growth concentrated in a small cluster of countries
- **Social:** Countries with higher healthcare expenditure per capita consistently show better life expectancy outcomes, though with diminishing returns beyond a threshold
- **Environmental:** CO2 emissions are declining in most developed nations but rising sharply in rapidly industrialising economies; renewable energy share correlates inversely with energy consumption growth
- **Technological:** Internet penetration and smartphone adoption are the fastest-growing indicators globally, with emerging markets closing the gap quickly
- **Military:** Military expenditure as a share of GDP varies widely — some nations with smaller economies maintain disproportionately large active personnel counts

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Tableau Desktop | Dashboard design, calculated fields, parameter controls, visualisations |
| Tableau Public | Publishing and sharing dashboards |
| CSV | Source data (`country_comparison.csv`) |
| Parameters & Calculated Fields | Dynamic indicator group switching across dashboards |

---

## 🗂️ Dataset — 36 Indicators Across Countries & Years

| Category | Indicators |
|----------|-----------|
| **Economic** | GDP (Trillions USD), GDP per Capita (USD), Inflation Rate (%), Unemployment Rate (%), Labor Force Participation Rate (%) |
| **Social** | Population (Millions), Population Growth Rate (%), Urban Population (%), Life Expectancy (Years), Healthcare Expenditure per Capita (USD), Doctor-to-Patient Ratio, Literacy Rate (%), Education Expenditure as % of GDP, Poverty Rate (%), Gender Equality Index, Crime Rate (per 100,000) |
| **Environmental** | CO2 Emissions (Million Metric Tons), Forest Coverage (%), Renewable Energy Share (%), Energy Consumption (TWh), Agricultural Land (%) |
| **Technological** | Internet Penetration (%), Smartphone Adoption (%), Number of Airports, Road Network Length (km), Public Transport Usage (%) |
| **Military** | Military Expenditure (Billion USD), Active Military Personnel |
| **Governance** | Human Development Index (HDI), Corruption Perception Index, Freedom of Press Index, Voting Participation Rate (%) |
| **Tourism** | International Visitors (Millions), Tourism Revenue (Billion USD) |

---

## 📁 Repository Structure

```
Economic Analysis/
├── data/
│   └── country_comparison.csv            # Source dataset (36 indicators)
├── tableau/
│   └── Global_Performance_Dashboard.twbx # Tableau packaged workbook
├── screenshots/
│   ├── home.png
│   ├── economic_dashboard.png
│   ├── social_dashboard.png
│   ├── environmental_dashboard.png
│   ├── technological_dashboard.png
│   └── military_dashboard.png
└── README.md
```

---

## ▶️ How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Amudha25/Data-Analytics-Portfolio.git
   cd "Data-Analytics-Portfolio/Economic Analysis"
   ```
2. **Open the Tableau file** — Open `Global_Performance_Dashboard.twbx` in Tableau Desktop or Tableau Public
3. **Explore** — Use the Home dashboard to navigate to each indicator group; use the Indicator Group parameter and country/year filters to drill into specific nations and trends

> 💡 **Don't have Tableau Desktop?** Download [Tableau Public](https://public.tableau.com/en-us/s/download) for free — it opens `.twbx` files at no cost.

---

## 📂 Data Source

- Country Comparison Dataset (`country_comparison.csv`) — compiled multi-source global indicators dataset covering economic, social, environmental, technological, military, and governance metrics by country and year

---

## 👩‍💻 Author

**Amudha Devi M.**  
Data Analyst | Power BI Developer  
📧 amumahes@yahoo.com.sg  
🔗 [LinkedIn](https://www.linkedin.com/in/amudhadevi/) | [GitHub Portfolio](https://github.com/Amudha25/Data-Analytics-Portfolio)
