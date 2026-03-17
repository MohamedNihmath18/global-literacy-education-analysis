
# Global Literacy & Education Trends Analysis

## Project Overview
Analysis of global literacy rates, GDP, gender gaps
and education trends across 180+ countries (1990-2023)
using Python, SQL and Power BI.

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (SQLite)
- Power BI
- Google Colab & Jupyter Notebook

## Project Structure
```
├── 01_data_collection_colab.ipynb
├── 02_main_analysis.ipynb
├── data/
│   ├── df_literacy.csv
│   ├── df_illiteracy.csv
│   └── df_gdp_schooling.csv
├── charts/
│   ├── plot1_adult_literacy_dist.png
│   ├── plot2_top_bottom10.png
│   ├── plot3_gdp_dist.png
│   ├── plot4_gender_gap_box.png
│   ├── plot5_gdp_vs_literacy.png
│   ├── plot6_literacy_trend.png
│   ├── plot7_schooling_vs_literacy.png
│   ├── plot8_correlation_heatmap.png
│   ├── plot9_global_illiteracy_trend.png
│   └── plot10_gender_gap_countries.png
├── database/
│   └── global_literacy.db
└── dashboard/
    └── Global_Literacy_Dashboard.pbix
```

## Dataset Sources
Data collected from Our World in Data (OWID):
- Adult Literacy Rate
- Youth Literacy Rate (Male & Female)
- Illiteracy Population
- GDP per Capita
- Average Years of Schooling

## Key Findings
1. Global adult literacy improved from 75% to 87% (1990-2023)
2. Strong positive correlation between GDP and literacy (r > 0.7)
3. Gender literacy gap is closing but persists in low-GDP regions
4. Sub-Saharan Africa has highest illiteracy rates globally
5. More schooling years generally leads to higher literacy rates

## EDA Charts
- Distribution of adult literacy rate
- Top 10 and Bottom 10 countries by literacy
- GDP per capita distribution
- Gender gap analysis
- Literacy trends over time
- Correlation heatmap

## SQL Queries
13 SQL queries covering:
- Top performing countries
- Gender literacy gaps
- GDP vs education analysis
- Regional comparisons
- Join queries across tables

## Power BI Dashboard
4-page interactive dashboard:
- Page 1: Global Overview
- Page 2: Gender and Youth Analysis
- Page 3: GDP and Economic Analysis
- Page 4: Illiteracy Deep Dive
