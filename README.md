# EV Charging Network Dashboard

A professional Excel dashboard analyzing the performance and usage of EV charging stations. Built with **Power Query** and **PivotTables / PivotCharts**, featuring KPIs, interactive slicers, and clean visualizations for portfolio showcase.

---

## Project Overview
This project demonstrates **data cleaning, feature engineering, and dashboard creation** using real-world EV charging station data. It focuses on deriving actionable insights for operators, users, and stakeholders.

---

## Data Description

**Original Columns:**  
`Station ID | Latitude | Longitude | Address | Charger Type | Cost (USD/kWh) | Cost Category | Availability | Duration in Hours | Distance to City (km) | Usage Stats (avg users/day) | Station Operator | Charging Capacity (kW) | Connector Types | Installation Year | Renewable Energy Source | Reviews (Rating) | Parking Spots`

**Engineered Columns (Power Query):**  
- `Maintenance Frequency` → numeric, cleaned  
- `Station Age` → 2025 - Installation Year  
- `Usage Category` → Low / Medium / High  
- `Distance Category` → Near / Medium / Far  
- `Charger Speed Category` → Slow / Medium / Fast  
- `Cost Efficiency` → custom metric based on users per cost  
- `Usage Efficiency` → custom metric based on usage per kW

---

## Dashboard Features

### Key Performance Indicators (KPIs)
- **Avg Cost per kWh**  
- **Avg Usage (avg users/day)**  
- **Total Capacity (kW)**  
- **Avg Maintenance Frequency**  

### PivotCharts / Visuals
1. **Installation Year → Adoption Trend (Line Chart)**  
   - Shows growth of EV stations over time

2. **Charger Type Distribution (Column Chart)**  
   - Visualizes the mix of charger technologies deployed

3. **Operator-wise Usage (Bar Chart)**  
   - Shows average station usage per operator

### Slicers
- Station Operator  
- Charger Type  
- Connector Type  
- All PivotCharts respond dynamically to slicer selections

---

## Tools Used
- **Microsoft Excel**  
  - Power Query (PQ) → data cleaning and feature engineering  
  - PivotTables / PivotCharts → KPIs and interactive visualizations  
  - Slicers → dynamic filtering  

---

## How to Use
1. Open the `EV_Charging_Dashboard.xlsx` file.  
2. Interact with the **slicers** to filter charts by operator, charger type, or connector type.  
3. Review the **KPI cards** at the top for high-level insights.  
4. PivotCharts automatically update based on slicer selections.

---

## Project Files
- `detailed_ev_charging_stations.xlsx` → cleaned source data  
- `EV_Charging_Dashboard.xlsx` → interactive dashboard with KPIs, PivotCharts, and slicers

---

## Insights / Takeaways
- EV station adoption has steadily increased over time.  
- Usage varies significantly by operator and charger type.  
- KPIs allow quick assessment of cost, usage, capacity, and maintenance trends.
