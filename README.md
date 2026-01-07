# Eskom Data Analysis

## Overview
This project analyzes South Africa’s electricity system using the **ESK2033 hourly dataset**, covering the period from **April 2018 to March 2023**.  
The objective is to uncover trends and understand electricity demand, export/import and generation patterns to make informed business insights.

### Dashboards overview
![Eskom Data Analysis](powerbi/visuals/overview.png)
![Eskom Data Analysis](powerbi/visuals/electricity_generation.png)
![Eskom Data Analysis](powerbi/visuals/renewable.png)
![Eskom Data Analysis](powerbi/visuals/exports_and_demands.png)

##  Project Objectives
- Clean and prepare raw Eskom data using Microsoft Excel for analysis.
- Transform wide-format data into a tidy, analysis-ready structure.
- Perform exploratory data analysis using PivotTables.
- Build a professional and interactive dashboard using Power BI.
- Communicate insights clearly using data visualization.

## Dataset
### ESK2033.csv

### Cleaning steps:
1. Imported raw CSV data into Power Query
2. Converted the date column to a proper DateTime format
3. Extracted:
   - Year
   - Month
   - Month Name
   - Day
   - Hour
4. Handled missing values:
   - Generation and unit-hour columns replaced with `0`
5. Renamed columns for clarity and consistency
6. Created calculated columns:
   - Total Renewable Generation (Wind + Solar)
   - Total Pumped Storage Generation
   - Net Imports (Imports − Exports)
   - Total Generation
## Business Questions
-When does demand peak during the year?
-How much does South Africa rely on imports?
-How reliable are renewables compared to thermal?
-What hours show the highest system stress?
