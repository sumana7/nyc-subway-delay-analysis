# NYC Subway Delay Analysis

## Overview

This project analyzes operational patterns and key drivers of subway delays in New York City between 2020 and 2026. The objective was to understand delay distribution, identify major contributing factors, and examine temporal trends in order to derive actionable operational insights.

The project integrates **Power BI for data transformation and dashboard visualization** with **Python (Pandas, Matplotlib, Seaborn)** for structured exploratory analysis and insight validation.

---
## Problem Statement

Subway delays significantly impact daily commuters, operational efficiency, and infrastructure planning. However, understanding when delays occur, how severe they are, and what drives them is essential for improving system reliability.

This project aims to answer:
- How are subway delays distributed?
- Are weekday delays different from weekend delays?
- How did delay trends change over time?
- What operational categories contribute most to total delays?

---
## Data Source
Publicly available NYC MTA subway delay datasets (2020–2026).

The dataset includes:
- Delay counts
- Reporting categories (infrastructure, crew, police/medical, etc.)
- Division and line information
- Month, year, and quarter breakdowns

---
## Tools & Technologies
- **Power BI** – Data cleaning (Power Query) and dashboard creation  
- **Python (Pandas, Matplotlib, Seaborn)** – Exploratory Data Analysis  
- **GitHub** – Version control and documentation  

---
## Project Workflow

### Stage 1: Data Preparation (Power BI)
- Cleaned raw dataset using Power Query
- Created Year, Month, Quarter features
- Standardized reporting categories
- Exported processed dataset for Python analysis
- Built interactive dashboard visuals

### Stage 2: Exploratory Analysis (Python)
- Analyzed delay distribution
- Compared weekday vs weekend variability
- Examined monthly time trends
- Identified primary delay drivers by category
- Derived operational recommendations

---
### Project Structure
NYC-SUBWAY-DELAY-ANALYSIS/
│
├── dashboard_assets/
│ ├── division_breakdown.png
│ ├── severity_by_category.png
│ ├── trend_over_time.png
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── 01_data_loading_and_cleaning.ipynb
│ ├── 02_exploratory_data_analysis.ipynb
│ └── 03_business_summary_and_recommendations.ipynb
│
├── NYC_Subway_Delay_Analysis.pbix
├── README.md


---
## Key Insights

### 1. Delay Distribution
Subway delays are highly right-skewed. Most delay periods involve relatively low disruption counts, while a small number of extreme events contribute disproportionately to total delays.

### 2. Weekday vs Weekend Differences
Weekday delays exhibit higher median values and significantly greater variability compared to weekends, suggesting increased operational complexity during workdays.

### 3. Pandemic Impact
A sharp decline in delays occurred in early 2020, reflecting reduced subway operations during COVID-19. Delays increased in subsequent years and stabilized at higher levels as ridership recovered.

### 4. Primary Delay Drivers
Infrastructure and equipment issues represent the largest contributor to total delays, followed by police/medical incidents and planned maintenance work. External factors contribute comparatively less.

---
## Business Recommendations

- Prioritize infrastructure investment and preventive maintenance to address the largest delay category.
- Strengthen weekday operational monitoring and contingency planning.
- Optimize planned maintenance scheduling to reduce passenger impact.
- Investigate patterns of extreme delay events for improved response planning.

---
## Dashboard Preview

### Monthly Delay Trend
![Trend Over Time](dashboard_assets/trend_over_time.png)

### Delay Severity by Category
![Severity by Category](dashboard_assets/severity_by_category.png)

### Division Breakdown
![Division Breakdown](dashboard_assets/division_breakdown.png)

---
## How to Reproduce the Analysis
1. Clone the repository
2. Install required packages:
3. Open and run notebooks in order:
   - `01_data_loading_and_cleaning.ipynb`
   - `02_exploratory_data_analysis.ipynb`
   - `03_business_summary_and_recommendations.ipynb`

---

## Project Outcome
This analysis demonstrates the ability to:

- Perform structured exploratory data analysis
- Interpret operational data in a business context
- Integrate BI tools with Python workflows
- Translate analytical findings into actionable recommendations



## Project Structure

