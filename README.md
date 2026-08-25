# 📊 Financial Health & Profitability Dashboard

**CodeAlpha Power BI Data Analytics Internship — Task 1**[cite: 1]

---

## 📌 Project Overview
An interactive Power BI dashboard developed to analyze and monitor organizational financial health, operational costs, profit margins, and multi-year revenue trends for strategic decision-making[cite: 1].

---

## 🖼️ Dashboard Preview
![Dashboard Preview](task1_dashboard.png)

---

## 🔑 Key Features & Analytical Insights
* **Executive Financial KPIs:** High-level tracking of Gross Sales, Net Revenue, COGS, and Overall Profitability Margins[cite: 1].
* **Profitability & Cost Analysis:** Breakdown of Cost of Goods Sold (COGS) versus Net Profit across business segments and product tiers[cite: 1].
* **Geographic Breakdown:** Multi-country comparative performance assessing revenue distribution across international markets[cite: 1].
* **Financial Forecasting:** Historical trend evaluation enabling predictive budgeting and operational cost controls[cite: 1].
* **Dynamic Slicers:** Multi-attribute filtering across Country, Segment, and Date hierarchies[cite: 1].

---

## 🧹 Data Cleaning & Preprocessing (Power Query)
* Formatted currency and numerical types across financial transaction fields (`Gross Sales`, `Discounts`, `COGS`, `Profit`)[cite: 1].
* Handled missing discount values and verified negative profit records for accurate margin calculation[cite: 1].
* Extracted date dimensions (`Year`, `Month Number`, `Month Name`) to support continuous timeline trend forecasting[cite: 1].

---

## 🛠️ Tech Stack & Tools
* **BI Platform:** Microsoft Power BI Desktop[cite: 1]
* **Analytical Modeling:** DAX (Data Analysis Expressions)[cite: 1]
* **ETL Transformation:** Power Query[cite: 1]
* **Source Data:** Financial Sample Dataset (`.xlsx`)[cite: 1]

---

## 📁 Repository Structure
```text
├── CodeAlpha_FinancialHealthDashboard.pbix   # Power BI Report File
├── 04-01-Financial Sample Data.xlsx           # Source Dataset
├── task1_dashboard.png                        # Dashboard Screenshot
└── README.md                                  # Project Documentation
