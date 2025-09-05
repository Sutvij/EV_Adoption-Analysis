# ⚡ ElectriVue: Electric Vehicle Population Analysis Dashboard

A dynamic, interactive Power BI dashboard built to analyse the adoption, performance, and demographic distribution of over 150,000 electric vehicles across the United States.

![Power BI Dashboard](https://github.com/Sutvij/EV_Adoption-Analysis/blob/main/EV_Adpotion_Analysis.pbit)

![Power BI Dashboard Screenshot](https://github.com/Sutvij/EV_Adoption-Analysis/blob/main/EV_Adoption%20Trend.png)

## 📖 Project Overview

The **ElectriVue Dashboard** is a comprehensive analytical tool designed to explore and visualize the growing electric vehicle (EV) market. It enables users to track key adoption trends, compare vehicle performance by make and model, and understand regional distribution patterns.

This dashboard is intended for use by:
- **Automotive Industry Analysts**
- **Sustainability Researchers**
- **Policy Makers**
- **Data Enthusiasts**

## 🛠️ Tech Stack

- **📊 Power BI Desktop** - Primary development platform for report design and visualization.
- **📂 Power Query** - Used for data extraction, transformation (ETL), and cleaning.
- **🧠 DAX (Data Analysis Expressions)** - Created calculated measures (KPIs, percentages, dynamic formatting).
- **📝 Data Modeling** - Established a single-table model with applied filters for accurate analysis.
- **🎨 Custom Visual Design** - Utilized shapes and a custom green-themed color palette for a cohesive UI.

## 📁 Data Source

- **Source:** [Electric Vehicle Population Data]([https://www.kaggle.com/datasets/](https://www.kaggle.com/datasets/willianoliveiragibin/electric-vehicle-population?resource=download)) on Kaggle.
- **Description:** This dataset contains registration information for over 150,000 Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) through the year 2024.
- **Key Attributes:** `Vehicle ID`, `City`, `State`, `Model Year`, `Make`, `Model`, `Electric Vehicle Type`, `Electric Range`, `CAFV Eligibility`.

## 🚀 Features & Insights

### Business Problem
The automotive industry is rapidly transitioning to electrification. Stakeholders need clear insights into market adoption, manufacturer competition, geographic distribution, and vehicle performance to make informed decisions.

### Solution: Interactive Dashboard
This dashboard provides an intuitive visual story of the EV market, answering key business questions through interactive visuals.

### Key Visuals & Metrics

| | |
| :--- | :--- |
| **📈 Adoption Over Time**<br>An area chart tracking the strong year-over-year growth of EV registrations from 2011 to 2023. | **🗺️ Geographic Hotspots**<br>A shape map highlighting U.S. states with the highest EV concentrations (e.g., Washington). |
| **🏆 Top Manufacturers**<br>A bar chart ranking the top 10 automotive makes (e.g., Tesla, Nissan, Chevrolet) by their number of registered EVs. | **🔋 BEV vs. PHEV Breakdown**<br>Donut charts showing that **78%** of vehicles are pure electric (BEV), while **22%** are plug-in hybrids (PHEV). |
| **⚙️ Model Popularity**<br>A treemap visualizing the top 10 most registered models (e.g., Tesla Model Y, Model 3). | **✅ Regulatory Status**<br>A donut chart analyzing Clean Alternative Fuel Vehicle (CAFV) eligibility. |

### Interactive Features
- **Dynamic Slicers:** Filter the entire dashboard by `City`, `Electric Utility`, and `Electric Vehicle Type`.
- **Cross-Filtering:** Click on any visual (e.g., a specific manufacturer) to filter all other visuals on the page, enabling deep-dive analysis.

### Derived Insights
- **Market Trend:** The consistent upward trend in the area chart confirms the rapid growth of EV adoption, justifying further investment in EV infrastructure.
- **Manufacturer Strategy:** Clicking on "Tesla" reveals its strategy is 100% focused on BEVs with a high average range, while other brands like BMW have a more hybrid-focused approach.
- **Consumer Preference:** The high percentage of BEVs indicates strong market confidence in pure electric technology and range capability.

## 📋 How to Use
1. **Download the `.pbix` file** from the repository releases (if provided).
2. Open the file using **Power BI Desktop**.
3. Interact with the dashboard by:
    - Using the slicers at the top to filter by location or vehicle type.
    - Clicking on charts to cross-filter and explore specific segments of the data.

## 🔮 Future Enhancements
- Incorporate live data API feeds for real-time analysis.
- Add a "Price Analysis" page comparing EV costs against traditional vehicles.
- Include a predictive forecast model for future adoption rates.

---
