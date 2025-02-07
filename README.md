# Hospital Readmission Analysis: Trends, Costs, and Demographics

A Power BI dashboard and synthetic dataset demonstrating how to analyze hospital readmissions, treatment costs, and patient demographics.

## 1. Overview

This repository contains:
- **synthetic_healthcare_data.csv**: A synthetic dataset of 10,000 patient records.
- **healthcare_synthetic_data_generator.ipynb** (or `.py`): Python/Colab script used to generate the CSV.
- **hospital_readmission_analysis.pbix**: The final Power BI report showing key visuals and insights.

The primary goal is to explore:
- **Which conditions have the highest readmission rates**  
- **Cost vs. readmission correlation**  
- **Demographic breakdown of readmitted patients**  
- **Readmission trends over time**

## 2. Dataset Details

- **Age**: Bounded between 18–90
- **Gender**: Male/Female
- **Condition**: Example conditions (Diabetes, Heart Disease, COPD, etc.)
- **Readmission_Status**: 1 (readmitted) or 0 (not readmitted)
- **Total_Cost**: Treatment cost in USD
- **Discharge_Date**: Dates spanning 2020 to 2023
- **Region**: North, South, East, or West

### Generating the Synthetic Data
The Python script (or notebook) uses:
- **Numpy** for random distributions
- **Pandas** for data handling
- **Datetime** for spreading the discharge dates

## 3. Power BI Report

You can open the **.pbix** file in Power BI to see:
1. **Bar Chart**: Readmission Rate by Condition  
2. **Scatter Plot**: Avg Cost vs. Readmission Rate by Condition  
3. **Pie Chart**: Age/Gender distribution of readmitted patients  
4. **Line Chart**: Monthly or yearly readmissions


