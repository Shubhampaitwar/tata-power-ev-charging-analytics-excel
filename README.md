

Tata Power EV Charging Infrastructure Analysis

By Shubham Paitwar

An end-to-end analytics project evaluating the performance, profitability, operational efficiency, and expansion potential of EV charging infrastructure across districts, built for Tata Power.

---

📌 Objective

To analyze EV charging demand, station utilization, financial performance, and expansion opportunities in order to support data-driven infrastructure planning.

Goals:
- Monitor EV charging demand
- Analyze charging station utilization
- Evaluate financial profitability
- Identify high-demand locations
- Support infrastructure expansion decisions
- Improve operational efficiency

🎯 Business Problem

Tata Power wanted to understand:
- How EV charging demand is growing
- Whether existing stations can handle future demand
- Which stations are overutilized vs. underperforming
- Customer charging behavior patterns
- Which districts provide the highest ROI
- Infrastructure gaps across districts
- Best locations for future expansion

🗃️ Dataset Overview

| Table | Key Fields |
|---|---|
| Charging Sessions | Session ID, kWh Charged, Revenue, Charging Duration |
| Station Details | Station ID, District, Plug Count |
| Customer Details | Customer ID, Income Tier |
| EV Details | EV Model, Battery Capacity |
| Financial Data | CAPEX, ROI, EBITDA |

🧹 Data Preparation & Modeling

1. Data Collection – imported and combined the five source tables above.
2. Data Cleaning – removed duplicates, handled missing values, corrected inconsistent entries, standardized column names, and verified data types.
3. **Data Transformation** – derived Month/Quarter/Year fields, categorized sessions by time of day, grouped customers by income tier, and binned battery capacities into ranges.
4. Data Modeling – built relationships across tables using Session ID, Station ID, Customer ID, and District to enable accurate KPI calculations and cross-filtering.

📊 Dashboard Structure

The analysis is delivered as a 4-page interactive dashboard:

Page 1 — Business & Usage Overview
- Charging demand trends by month and day
- Station capacity vs. growing demand
- Charging behavior patterns by time of day
- KPIs: Total Sessions (1,14,000) · Total Energy Consumed (28,59,772 kWh) · Total Revenue (₹4,96,93,947) · Active Customers (8,000) · Avg. Revenue/Session (₹436) · Avg. kWh/Session (25)

Page 2 — Station Utilization & Operational Efficiency
- Overutilized vs. underutilized station analysis
- Plug utilization efficiency across locations
- Load distribution across districts and stations
- KPIs: Sessions per Station · Avg. Utilization per Station · Plugs Count vs. Actual Usage · Avg. kWh per Station · Station Density · Sessions-per-Plug Ratio

Page 3 — Customer & Demand Behavior
- Usage and revenue contribution by income tier
- Charging behavior by income tier
- Usage patterns across EV models and battery capacities
- KPIs: Sessions per Customer · Avg. kWh per Customer · Unique Customer Count (3,879) · Revenue per Customer (₹465.98) · Usage by Income Tier · Usage by Car Model/Battery Capacity

Page 4 — Financial Performance & Expansion Strategy (ROI Focus)
- Top districts by ROI %
- Payback period by charging setup (AC Level-2, DC Fast, DC Ultra-Fast)
- High-potential locations by demand and ROI
- KPIs: CAPEX per Project (₹664) · Annual Revenue (₹290) · EBITDA (₹204) · Payback Period With/Without Subsidy · 5-Year ROI % (329.6)

## 🔑 Key Findings

- EV charging demand is steadily increasing, with significant energy consumption across major districts.
- "Yelahanka, Rajajinagar, Jayanagar, HSR Layout, and Koramangala" show signs of capacity constraints and should be prioritized for expansion.
- "Anekal and Byatarayanapura" are underutilized — usage should be improved before adding capacity.
- "Mid-Range income tier" customers drive the highest charging usage and revenue.
- "29.2 kWh and 66.5 kWh" battery capacity EVs account for the highest charging activity.
- "Bommanahalli, Banashankari, Jayanagar, and Yelahanka" deliver the strongest ROI and are the best candidates for future investment.

✅ Final Recommendation

Tata Power should focus on expanding charging infrastructure in high-demand, high-ROI districts while improving utilization in underperforming locations. A balanced strategy combining demand forecasting, operational optimization, and ROI-driven investments will support sustainable growth, better customer experience, and long-term profitability of the EV charging network.

🛠️ Tools Used

- Excel / Power Pivot — data cleaning, modeling, and KPI/measure creation
- Pivot Tables & Charts — trend, utilization, and behavioral analysis
- Dashboard reporting across 4 focused business pages

📁 Repository Contents

- `Milestone_Project-1_edited.pptx` — full project presentation with dashboards, insights, and analysis

---


