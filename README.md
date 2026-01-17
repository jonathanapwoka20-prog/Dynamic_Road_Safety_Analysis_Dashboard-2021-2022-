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
* **Year-over-Year Trends:** Identified specific months where casualties peaked in **2022** compared to **2021**. In **November 2021**, the Casualties peaked at the highest **(20,975)** while the same month in **2020**, the the number stood at **18,439**. Both months in both years recorded the highest casualty rates which can be attributed to the holidays festive season as from **November to December** and people travelling around the country in high numbers and not maintaining traffic rules and regulations.
* **Casualty Hotspots:** Established a clear relationship between **Road Type** and **Casualty Volume**. **Single Carriageway** roads led in the number of casualties recorded **(309,698).**
* **Visibility Analysis:** Determined the correlation between **Day/Night** conditions and **casualty rates** across locations since casualties recorded during the day stood at **305K** of the total **417.8K** casualties, more than double those recorded during the night. Additionally, the number of casualties were recorded to be higher in **urban areas (259.9K**) than in **rural areas (162K)**. This can be attributed to factors such as; more people living or working in urban areas where travelling is often needed to move from one location to another.

---

## Recommendations
- Implement targeted road safety campaigns and stricter traffic enforcement during high-risk festive months (November–December) to reduce seasonal casualty spikes.
- Prioritize infrastructure upgrades and safety interventions on Single Carriageway roads, which account for the highest casualty volumes.
- Optimize daytime traffic management through congestion control, peak-hour monitoring, and driver behavior enforcement to address higher daytime casualty rates.
- Focus urban-specific road safety strategies, including pedestrian protection and traffic flow optimization, due to significantly higher casualties in urban areas.
- Use analytics dashboards and historical data to support continuous monitoring, risk forecasting, and evidence-based road safety decision-making.

---
## Conclusion
This project demonstrates the ability to **synthesize complexity** (making 300K rows readable), **ensure data reliability** (validating a "Single Source of Truth"), and **drive action** (creating tools for specific stakeholders to make data-backed decisions).

## 📂 Access & Interact with the full Dashboard
You can view the full interactive dashboard by downloading the file below:
[🔗 Download Road Accident Data Analysis & Dashboard Excel file)](https://docs.google.com/spreadsheets/d/1lT20kP0tlKZGSE8SOJbLX0Vfu3GvgU_s/edit?usp=drive_link&ouid=103170821742347333212&rtpof=true&sd=true)
