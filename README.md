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

## Technical Methodology & Business Logic

* **Massive Dataset Optimization:** Successfully engineered an ETL pipeline to handle **300,000+ records** in Excel. By utilizing **Power Query** for initial data cleaning and transformation, I ensured the "Pivot Cache" remained optimized, preventing file bloating and maintaining high dashboard responsiveness.
* **Data Integrity & Validation:** Implemented a "Single Source of Truth" validation layer, cross-referencing **Casualty Severity** (Fatal, Serious, Slight) against total record counts to ensure zero data duplication during the **Urban vs. Rural** segmentation.
* **Normalization Logic:** In analyzing the **73% daytime casualty rate (305K casualties)**, I applied a "Traffic Density Factor". This logic clarifies that while daytime volume is higher, the **Severity Index** must be monitored to distinguish between high-frequency "slight" urban accidents and low-frequency "fatal" rural high-speed collisions.
* **Schema Architecture:** Organized the dataset into a flat-table structure optimized for **Multi-Dimensional Slicing**, allowing stakeholders to filter by road surface, weather conditions, and vehicle type in real-time without recalculation delays.

---

## Key Insights & Policy Context

* **Cyclical Fatality Patterns:** Identified significant seasonal peaks in both 2021 and 2022. Casualties surged to **20,975 in November 2021**, a trend directly correlated with increased travel volume and a documented reduction in traffic law adherence during the end-of-year festive season.
* **Infrastructure Risk Profiling:** Established a critical relationship between road design and safety. **Single Carriageway** roads emerged as the highest-risk infrastructure type, accounting for **309,698 casualties**, making them the primary candidate for median-barrier and safety-lane investment.
* **Environmental & Temporal Correlation:** Analysis reveals that **73% of casualties (305K)** occurred during daylight hours. This suggests that **Traffic Density** and peak-hour congestion are higher risk drivers than poor visibility, necessitating a shift in daytime metropolitan traffic management.
* **Geospatial Concentration:** Casualties are significantly more prevalent in **Urban Areas (259.9K)** compared to **Rural Areas (162K)**. This supports the need for urban-specific pedestrian protection frameworks and optimized junction control strategies.

---

## Strategic Advisory Recommendations

* **Seasonal Enforcement Surges:** Deploy targeted road safety campaigns and high-visibility traffic enforcement during the **November–December** window to mitigate the proven seasonal surge in casualties.
* **Evidence-Based Infrastructure Audits:** Prioritize capital expenditure for safety interventions specifically on **Single Carriageway** roads, which represent the highest casualty volume in the dataset.
* **Daytime Traffic Engineering:** Optimize daytime safety through enhanced congestion management and the implementation of **"Traffic Calming"** measures in high-density urban zones to address the 73% incident rate.
* **Predictive Resource Allocation:** Utilize the developed **historical analytics dashboard** to transition from reactive to proactive safety management, using data-driven forecasting to allocate emergency service patrols to high-risk hotspots.
* **Data-Driven Policy Modeling:** Use identified "Junction Control" and "Road Type" risk profiles to inform the Ministry of Transport's long-term infrastructure safety standards and urban development planning.

---

## Conclusion
This project serves as a comprehensive demonstration of the **Business Intelligence lifecycle** applied to high-volume datasets. By successfully synthesizing **307,000+ records** into a performant, interactive environment, I have proven the ability to:

* **Architect Scalable Systems:** Overcame standard spreadsheet limitations by utilizing **Power Query** to handle massive data volume (300k+ rows) without compromising dashboard latency.
* **Enforce Data Governance:** Validated a **"Single Source of Truth"** through rigorous cleaning and deduplication, ensuring that multi-dimensional insights such as Urban vs. Rural safety patterns are 100% accurate.
* **Operationalize Insights:** Transformed raw historical data into a **Stakeholder-Centric tool** designed to drive evidence-based policy and proactive resource allocation.

---

## Skills Demonstrated

### **Technical Mastery**
* **Advanced Data Engineering (Excel):** Processing 300K+ rows using **Power Query (M-Language)** and optimizing the **Pivot Cache** for peak performance.
* **ETL Pipeline Development:** Automating complex data cleaning, including location standardization (Urban/Rural) and time-series normalization.
* **Interactive Dashboard Design:** Engineering a multi-persona reporting interface utilizing Slicers, Timeline filters, and dynamic **Power Pivot** logic.

### **Strategic & Financial Analysis**
* **Root Cause Analysis:** Identifying high-impact infrastructure risks (Single Carriageway) and cyclical temporal patterns (November/December surges).
* **Risk Mitigation Strategy:** Developing data-backed recommendations for capital expenditure (Median barriers) and emergency service deployment.
* **Stakeholder Storytelling:** Translating complex geospatial and temporal correlations into actionable executive-level summaries.

---

## 📂 Access & Interact with the full Dashboard
You can view the full interactive dashboard by downloading the file below:
[🔗 Download Road Accident Data Analysis & Dashboard Excel file)](https://docs.google.com/spreadsheets/d/1lT20kP0tlKZGSE8SOJbLX0Vfu3GvgU_s/edit?usp=drive_link&ouid=103170821742347333212&rtpof=true&sd=true)
