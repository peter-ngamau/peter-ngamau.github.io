[Home](/) | [Projects](/projects) | [Contact](/contact)

# 📊 Featured Projects

## 1. Kenya Financial Inclusion & Mobile Money Analytics

**Tools:** Python · SQL Server · Power BI  
**Data:** Central Bank of Kenya · FinAccess Household Survey 2006–2024  
**Scope:** 47 counties · 10 years · 6 datasets · 4-page interactive dashboard

---

### What this project is about

Kenya has one of the most remarkable financial inclusion stories in the world. Since M-Pesa launched in 2007, the country went from **67.5% of its population being financially excluded** to just **9.9% today**. But behind that headline, millions of Kenyans — the elderly, rural communities, people without formal education — are still being left behind.

This project analyses 10 years of CBK mobile money data and 7 waves of the FinAccess Household Survey to find out exactly where the gaps are, who is most affected, and what is driving inclusion at the county level.

---

### What I built

A complete end-to-end analytics pipeline — from raw government data files to a published interactive dashboard.

**Data cleaning (Python)** — Six raw datasets were cleaned, validated and transformed using pandas. Every column was standardised, all 47 counties verified, percentage ranges checked, and derived metrics added including exclusion tiers, urban-rural gaps, and a relative exclusion index comparing each demographic segment against the national average.

**Exploratory analysis (Python)** — Eleven analytical charts were produced covering transaction growth trends, seasonal patterns, agent density correlations, demographic exclusion breakdowns, and the evolution of inclusion across seven survey waves from 2006 to 2024.

**Data warehouse (SQL Server)** — Clean data was loaded into a star schema with four dimension tables and five fact tables, loaded via a Python SQLAlchemy pipeline and verified with row count checks.

**Dashboard (Power BI)** — A four-page interactive report connecting directly to SQL Server, with a county filled map, scatter plots, trend lines, demographic breakdowns, DAX measures, and cross-filtering slicers.

---

### Key findings

- M-Pesa transaction value grew **7× in 10 years** — KES 1,238B in 2015 to KES 8,700B in 2024
- Mobile money transactions now equal **57.6% of Kenya's GDP**
- **Tana River County** has the highest exclusion rate at 37.6% — **Nyandarua** the lowest at 2.6%
- People with **no formal education** are **4.6× more likely** to be excluded than the national average
- The **2020 COVID-19 pandemic** drove the single largest adoption jump — **41% growth** in one year
- **Agent density and inclusion are positively correlated** — counties with more agents per 1,000 people consistently show higher inclusion rates

---
![Dashboard preview](Screenshorts/Fin1.png)
### Links

- 📂 [View full project on GitHub](https://github.com/peter-ngamau/Financial-Inclusion-In-Kenya)
- 📊 [View live Power BI dashboard](https://github.com/peter-ngamau/Financial-Inclusion-In-Kenya/blob/main/Financial_Inclusion_Ke_Dashboard.pbix)

---

*This project demonstrates end-to-end data analytics skills across the full pipeline — data engineering, exploratory analysis, SQL warehousing, and business intelligence visualisation — applied to a real-world financial inclusion problem in Kenya.*


### 2. Retail Sales Data Analysis Project
**The Problem:** The company had sales data, but it wasn’t clear which products were driving revenue, how sales were trending over time, or how customer behavior was impacting performance.
**The Tools Used:** SQL, Python, Power BI, Excel

**The Impact:** 
 
 **Key Findings:**
- A small group of products contributed the majority of total revenue
- Sales performance varied across different periods, showing clear trends
- Customer purchasing patterns highlighted opportunities for repeat sales

**Recommendations:**
- Focus on high-performing products to maximize revenue
- Reassess or optimize low-performing inventory
- Leverage customer insights for targeted marketing and retention strategies


🔗 [View the Dashboard/Summary](https://github.com/peter-ngamau/Retail-Sales-Project-End-to-End-/blob/main/My%20Project%20Power%20Bi(RetailSales).pbix) | 💻 [View the Code](https://github.com/peter-ngamau/Retail-Sales-Project-End-to-End-)

---

## 3. Football Results Analysis Project
**The Problem:** Hypothesis-Testing-with-Men 's-and-Women 's-Soccer-Matches

**The Tools Used:** Python

**The Impact:** The mean number of goals scored in women's international soccer matches is greater than men's.

🔗 [View the Dashboard/Summary](link-to-live-dashboard) | 💻 [View the Code](https://github.com/peter-ngamau/Hypothesis-Testing-with-Men-s-and-Women-s-Soccer-Matches/blob/main/notebooks/notebook.ipynb)


---

