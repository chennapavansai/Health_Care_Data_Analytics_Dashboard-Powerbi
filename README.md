# 🚬 Healthcare Smoking Risk Analysis Dashboard

An interactive Power BI dashboard analyzing how smoking habits impact health conditions 
and identifying high-risk patient groups through data-driven visualizations.

## 🎯 Overview

This project analyzes patient health data to understand the relationship between smoking 
behavior and organ health outcomes. Using Power BI, Power Query, and DAX, the dashboard 
transforms raw healthcare records into actionable insights — helping identify high-risk 
patient groups and supporting preventive healthcare strategies.

## 🛠️ Tech Stack

- **Tool:** Power BI Desktop
- **Data Prep:** Power Query
- **Calculations:** DAX (measures & calculated columns)
- **Modeling:** Relational data modeling across multiple tables

## 📊 Dataset

- **Size:** ~2,500 patient records
- **Fields:** Patient ID, Age, Gender, Smoking Status, Years of Smoking, Cigarettes Per 
  Day, BMI, Blood Pressure Risk, Cholesterol Level, Alcohol Consumption, Family History, 
  and organ condition data (heart, lungs, liver, kidneys, body)

## 🔍 Key Features

- **Data Cleaning:** Corrected missing headers, verified data types, resolved 
  inconsistencies, and converted image links into Web URL format
- **Data Modeling:** Built relationships across tables using Patient ID and Organ 
  Condition as keys
- **DAX Measures:** Total Patients, Average Age, Average BMI, and a custom Age Group 
  column for segmented analysis
- **Dynamic Organ Visualization:** Interactive slicers let users select an organ 
  (e.g., lungs, heart) and view healthy vs. damaged organ images based on condition
- **Visualizations:**
  - KPI Cards — Total Patients, Average Age, Average BMI
  - Donut Chart — Smoking Status distribution
  - Line Chart — Years of Smoking vs. Avg. Cigarettes Per Day across Age Groups
  - Ribbon Chart — Smoking Status by Gender
  - Stacked Column Chart — Cholesterol Level across Blood Pressure Risk categories

## 📈 Key Insights

- Current smokers represented a significant portion of the patient population
- Longer smoking duration correlated with higher average cigarettes per day
- Older age groups showed higher cholesterol levels and increased blood pressure risk
- Male patients showed slightly higher smoking rates than females
- Damaged organs were more common among long-term smokers

## 💼 Business Value

This dashboard enables healthcare organizations to:
- Monitor smoking-related health risks
- Identify vulnerable patient groups
- Support preventive healthcare decision-making
- Improve awareness through interactive, visual reporting

