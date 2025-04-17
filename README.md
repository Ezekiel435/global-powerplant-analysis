🌍 Global Power Plant Financial Analysis

A comprehensive data analytics project exploring global power plant trends using a dataset from Kaggle. This report analyzes power generation capacity, estimated output, fuel types, plant ownership, and renewable energy adoption using **Power BI**.

---

 📊 Project Overview

This project was developed to:

- Understand how power generation and capacity are distributed globally.
- Explore the transition to renewable energy sources.
- Identify top power-producing countries and companies.
- Visualize energy trends over time using interactive dashboards.

---

 🗂️ Dataset Information

- Source: [Kaggle - Global Power Plant Database]([https://www.kaggle.com/](https://www.kaggle.com/datasets/ramjasmaurya/global-powerplants))
- Fields Used:
  - `country_long`, `capacity in MW`, `generation_gwh_2021`, `primary_fuel`, `start date`, `owner of plant`, `latitude`, `longitude`
- Target Year: 2021
- Size: ~35,000 records

---

 🧹 Data Cleaning Summary

Performed using Power Query in Power BI:

- Filled blanks in `secondary fuel` and `other_fuel2` with **"Oil"**
- Dropped `other_fuel3` and `other generation_gwh` columns (entirely null)
- Replaced missing `start date` and `owner of plant` values with the **mode**
- Filled missing `estimated_generation_gwh_2021` with **239.11 GWh** (mode)
- Created a new column `Renew/nonRenew` to classify fuel types

---

 🎯 Objectives & Visualizations

1. Total Capacity and Generation by Country
   - Bubble map, Column chart, KPI cards

2. Top Electricity Generating Countries (2021)
   - Bar chart, Treemap

3. Most Used Fuel Types & Renewable Trends
   - Donut chart, Stacked bar chart

4. Renewable Energy Locations
   - Filtered map, Stacked column by country

5. **Top Plant Owners by Capacity**
   - Bar chart, Table view

6. Plant Commissioning Over Time
   - Line chart showing plant count by year

7. Power Capacity Trends Over Time
   - Area chart tracking global capacity growth

---

 📌 Key Insights

- The **United States and China** lead in capacity and generation.
- **Solar** is the most common plant type, but **Hydro** generates the most energy.
- Power plant growth peaked around **2000–2015**.
- **Cypress Creek Renewables** and **China Huaneng Group** are top owners.
- Renewables are rising globally but fossil fuels still dominate output.

---

 📁 Files Included

- `PowerPlant.pdf` – Dashboard overview
- `Power Plant Analytics Report.pdf` – Detailed analysis report
- `PowerPlant.pbix` - Power Bi file
- `README.md` – Project documentation

---

💡 Future Improvements

- Include predictive modeling for future energy demand
- Expand renewable classification to include hybrid plants
- Integrate live energy generation data (if available)

 📬 Contact

For questions, suggestions, or collaborations:

Ezekiel Bassey  
📧 ezekielbassey6@gmail.com  
