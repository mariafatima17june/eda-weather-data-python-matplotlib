# Weather Data Analysis | Exploratory Data Analysis with Python

## Project Overview
An exploratory analysis of 8,784 hourly weather observations to understand weather-condition frequency, temperature variation and relationships among humidity, wind speed, visibility and atmospheric pressure. The project turns raw weather readings into descriptive findings that can support operational awareness and further investigation.

## Business Problem
Weather measurements are difficult to interpret at scale without a structured view of common conditions and relationships between environmental variables. This project uses exploratory data analysis to summarise the observations and highlight patterns relevant to transport, outdoor operations and safety planning.

## Objectives
- Assess dataset structure and data quality.
- Identify the most frequently recorded weather conditions.
- Examine the distribution of temperature, humidity, wind speed, visibility and pressure.
- Measure relationships among numerical weather variables.
- Compare visibility and wind speed across weather categories.
- Translate findings into practical recommendations.

## Dataset
- **Records:** 8,784
- **Columns:** 8
- **Weather categories:** 50
- **Fields:** Date/Time, Temp_C, Dew Point Temp_C, Rel Hum_%, Wind Speed_km/h, Visibility_km, Press_kPa and Weather.
- **Coverage:** The notebook uses observations from 2012; station/location and source attribution are not documented in the notebook.

## Workflow
1. Loaded the CSV using pandas.
2. Inspected dimensions, columns, data types and descriptive statistics.
3. Checked missing values and duplicate records.
4. Standardised column names and prepared numeric, date/time and weather fields.
5. Analysed weather frequency and numerical distributions.
6. Compared temperature, visibility and wind speed across weather categories.
7. Used correlation analysis to examine relationships between numerical variables.
8. Interpreted findings and developed recommendations.

## Key Findings
- The notebook reports **8,784 observations**, **zero missing values** and **zero duplicate rows**.
- **Mainly Clear** is the most frequent weather label with **2,106 observations**, followed by Mostly Cloudy (2,069), Cloudy (1,728) and Clear (1,326).
- Average temperature is **8.80°C** (median 9.30°C; range -23.30°C to 33.00°C).
- Temperature and dew point have a strong positive correlation (**0.93**).
- Relative humidity and visibility have a negative correlation (**-0.63**).
- Snow and blowing-snow categories show relatively higher wind speeds and reduced visibility in the category summaries.

## Tools & Skills
**Python, pandas, NumPy, Matplotlib, EDA, data cleaning, data quality checks, descriptive statistics, correlation analysis, data visualisation, business interpretation.**

## Repository Structure
```text
weather-data-analysis/
├── dataset/
│   └── Dataset_Weather_Analysis.csv
├── notebook/
│   └── Weather_Data_Analysis.ipynb
├── README.md
└── report/
    └── Weather_Data_Analysis_Project_Report.docx


