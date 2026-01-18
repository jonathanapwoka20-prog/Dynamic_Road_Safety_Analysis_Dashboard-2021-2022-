# Dynamic Road Safety Analysis Dashboard (2021-2022)

## Project Overview
**Headline:** Transforming 300K+ Public Records into Actionable Safety Insights via Advanced Excel Modeling.

* **Project Type:** End-to-End Data Analysis Initiative
* **Tools Used:** Microsoft Excel (Used Power Query for data cleaning , Pivot Tables, Slicers, Dynamic Linking)
* **Data Source:** Kaggle (Reported Road Casualties Great Britain)

---

## Context and Challenge
The objective was to analyze road accident data from 2021 and 2022 to identify high-risk factors influencing casualty rates. The goal was to build a centralized, interactive dashboard to monitor **Casualty Trends**, **Accident Severity**, and **Environmental Influences**.

### Primary KPI Requirements:
* **Casualty Magnitude:** Total casualties post-accident.
* **Severity Distribution:** Comparative analysis (% of Total) for Fatal, Serious, and Slight casualties.
* **Vehicle Impact:** Identifying vehicle types contributing to maximum casualties.

---

## Stakeholder Analysis
I designed this dashboard with specific end-users in mind to ensure the "pain points" were addressed:
* **Ministry of Transport:** To allocate infrastructure budgets based on "Road Type" risk profiles.
* **Emergency Services:** To optimize patrol schedules during peak high-risk "Day/Night" periods.
* **NGOs:** To drive awareness campaigns for high-risk vehicle types (e.g., Motorcycles).
* **Urban Planners:** To evaluate the effectiveness of "Junction Controls" in urban vs. rural areas.

---

## The Process Taken

### 1. Data Engineering & Integrity
Ensuring 100% data validity was critical:
* **Validation:** Removed duplicates and corrected misspellings via Filter and Find & Replace.
* **Date Standardization:** Generated Helper Columns for Year and Month to enable **Year-over-Year (YoY)** comparisons.

### 2. Strategic Data Modeling (Grouping)
I simplified complex categorical data to prevent dashboard clutter:
* **Vehicle Consolidation:** Grouped diverse entries into Cars, Buses, Vans, and Motorcycles.
* **Road Surface:** Merged conditions into macro-groups (Dry, Wet, Snow/Ice).

### 3. Advanced Dashboard Architecture
* **Secondary Staging Tables:** Extracted data from Pivot Tables into dedicated reporting tables to increase performance.
* **Dynamic UI:** Linked KPI cards and mini-charts to these staging tables, allowing for seamless, real-time updates via Slicers.

---

## Dashboard Preview & Technical Evidence

### 1. Main Interactive Dashboard
*A high-level view of all KPIs, including casualty trends and severity distribution.*

<img width="1920" height="957" alt="Screenshot 2026-01-07 012720" src="https://github.com/user-attachments/assets/2401c5fa-5f64-4b67-af7a-60e5a219d7d9" />

### 2. Pivot Staging & Modeling
*The Backend of the dashboard showing how staging tables drive the dynamic visuals.*

<img width="1920" height="1020" alt="Screenshot 2026-01-07 012742" src="https://github.com/user-attachments/assets/c57b0ad1-86a6-4ed1-8ca9-151aeb671636" />

<img width="1920" height="1020" alt="Screenshot 2026-01-07 012814" src="https://github.com/user-attachments/assets/aa6fd4bc-d352-46ef-bbc0-967d0f1c5935" />

---

## Key Insights

* **Cyclical Fatality Patterns:** Identified significant seasonal peaks in both 2021 and 2022. Casualties surged to **20,975 in November 2021** (compared to 18,439 in November 2020), a trend directly correlated with increased travel volume and reduced traffic law adherence during the end-of-year festive season.
* **Infrastructure Risk Profiling:** Established a critical relationship between road design and safety. **Single Carriageway** roads emerged as the highest-risk infrastructure type, accounting for a staggering **309,698 casualties**.
* **Environmental & Temporal Correlation:** Analysis reveals that daylight conditions do not mitigate risk; **305K casualties** (73% of the 417.8K total) occurred during the day, more than doubling nighttime rates. This suggests that traffic density and congestion are higher risk drivers than poor visibility.
* **Geospatial Concentration:** Casualties are significantly more prevalent in **Urban Areas (259.9K)** compared to **Rural Areas (162K)**. This concentration is attributed to higher population density, complex pedestrian-vehicle interactions, and frequent short-distance transit in metropolitan hubs.

---

## Strategic Recommendations

* **Seasonal Enforcement Surges:** Deploy targeted road safety campaigns and high-visibility traffic enforcement during the **November–December** window to mitigate the proven seasonal surge in casualties.
* **Infrastructure Safety Audits:** Prioritize capital expenditure for safety interventions—such as median barriers and improved signage—specifically on **Single Carriageway** roads to address the highest volume of incidents.
* **Daytime Traffic Engineering:** Optimize daytime safety through enhanced congestion management, stricter peak-hour monitoring, and the implementation of "Traffic Calming" measures in high-density zones.
* **Urban Pedestrian Protection:** Develop urban-specific safety frameworks focusing on pedestrian-heavy corridors and optimized traffic flow to address the higher incident rates in city centers.
* **Predictive Policy-Making:** Utilize the developed **historical analytics dashboard** to transition from reactive to proactive road safety management, using data-driven forecasting to allocate emergency resources efficiently.

---
## Conclusion
This project demonstrates the ability to **synthesize complexity** (making 300K rows readable), **ensure data reliability** (validating a "Single Source of Truth"), and **drive action** (creating tools for specific stakeholders to make data-backed decisions).

## 📂 Access & Interact with the full Dashboard
You can view the full interactive dashboard by downloading the file below:
[🔗 Download Road Accident Data Analysis & Dashboard Excel file)](https://docs.google.com/spreadsheets/d/1lT20kP0tlKZGSE8SOJbLX0Vfu3GvgU_s/edit?usp=drive_link&ouid=103170821742347333212&rtpof=true&sd=true)
