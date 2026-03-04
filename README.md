# NYC Subway Delay Analysis
**Tools:** Python (Pandas, Matplotlib, Seaborn) · Power BI · CSV

## Overview
Analysis of 17,171 NYC subway delay records spanning 2020–2026,
combining Python-based exploratory data analysis with Power BI
dashboard reporting. The project identifies delay trends, 
operational patterns, and primary disruption drivers across 
weekday and weekend operations.

## Business Questions Answered
- How are subway delays distributed across the network?
- Do weekday operations differ significantly from weekends?
- How did delays evolve over time, including during COVID-19?
- Which operational categories contribute most to total delays?

## Project Workflow

### 1. Data Cleaning (Power Query)
- Standardized date formats and categorical fields
- Handled missing values and outliers in delay records
- Prepared dataset for both Python EDA and Power BI reporting

### 2. Exploratory Data Analysis (Python)
- Delay distribution analysis (histogram + KDE)
- Weekday vs weekend comparison (box plots)
- Monthly trend analysis (2020–2026 line chart)
- Category-level delay aggregation (bar chart)

### 3. Dashboard (Power BI)
- Total delays and average delay KPI cards
- Monthly delay trend over time
- Weekday vs weekend performance comparison
- Category-wise delay contribution breakdown

## Key Findings

| Finding | Detail |
|--------|--------|
| Delay range | 1 to 1,836 per period |
| Mean delay | ~147 per period |
| Dataset size | 17,171 records |
| Top delay driver | Infrastructure & equipment issues |
| COVID impact | Sharp decline in early 2020, recovered by 2022 |
| Weekday vs Weekend | Higher median and variability on weekdays |

## Recommendations
- Prioritize infrastructure upgrades to address the leading 
  delay category
- Strengthen weekday operational monitoring given higher 
  peak variability
- Schedule planned maintenance during low-impact windows
- Build disruption response protocols around extreme delay events

## Files
| File | Description |
|------|-------------|
| `eda_subway_delays.ipynb` | Python EDA notebook |
| `subway_dashboard.pbix` | Power BI dashboard |
| `subway_trains_delayed_cleaned.csv` | Cleaned dataset |

## Skills Demonstrated
`Python` `Pandas` `EDA` `Matplotlib` `Seaborn` 
`Power BI` `DAX` `Trend Analysis` `Operational Analytics`
