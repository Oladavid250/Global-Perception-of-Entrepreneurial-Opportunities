# 🌍 Global Perception of Entrepreneurial Opportunities

## 📘 Project Overview
This project explores how individuals across different countries perceive opportunities for entrepreneurship. The goal was to clean, transform, and analyze global perception data, and visualize the results in a Power BI dashboard. This project highlights my skills in data cleaning, transformation, visualization, and storytelling — all critical components of a data analyst’s workflow.

---

## 🧩 Problem Statement
Governments, investors, and global policy makers lack consistent insights into how entrepreneurial opportunities are perceived around the world. Without these insights, it's difficult to shape effective economic and innovation policies. This project addresses the issue by creating a clean, visual, and interactive dashboard that compares entrepreneurial perception across nations and over time.

---

## 🗃️ Dataset
- **Source:** Global survey dataset (e.g., GEM or World Bank)
- **Format:** Excel (CSV/XLSX)
- **Key Fields:**  
  - `Country`  
  - `Year`  
  - `Perceived Opportunity Score`  
  - `Region` (added during transformation)

---

## 🧹 Data Cleaning (Excel)
- Removed duplicate and null entries  
- Normalized inconsistent country names (e.g., "USA" → "United States")  
- Converted `Year` column to numeric  
- Created additional calculated fields for trend analysis  
- Ensured consistent formatting for all columns

---

## 🔄 Data Transformation (Power Query)
- Imported cleaned dataset from Excel  
- Unpivoted year columns into long format (if required)  
- Grouped data by `Country` and `Year`  
- Added regional classifications using join operations  
- Removed outliers for better visual interpretation  
- Added ranking and average metrics per country

---

## 📊 Dashboard Features (Power BI)
- **KPI Cards**:  
  - Most Recent Year Avg: `20`  
  - Global Avg Perception: `14`  
  - Highest Country: `Spain`  
  - Lowest Country: `Russia`  

- **Time Series Analysis**:  
  - U.S. shows a steady decline from `42 (2016)` to `24 (2024)`

- **Bar Chart**:  
  - Top Countries by Perception: UK, Netherlands, Slovenia, etc.

- **Map View**:  
  - Regional variation in U.S. states (if dataset available)

- **Interactive Filters**:  
  - Country, Year, Report Type, Database

---

## 🔍 Key Insights
- European countries dominate top rankings in opportunity perception  
- Spain leads with the highest current score  
- The U.S. shows declining perception over time  
- Global average remains low, highlighting room for improvement  
- Russia has the lowest score among countries observed

---

## 🛠️ Tools Used
- **Microsoft Excel** – for initial cleaning  
- **Power Query** – for data transformation and shaping  
- **Power BI** – for dashboard and data visualization  

---

## ✅ Outcome
The final result is a polished, interactive dashboard that provides valuable global insights into entrepreneurial opportunity perception. It serves as a reference for stakeholders to assess where optimism exists — and where intervention may be needed.

---

## 🧠 Skills Demonstrated
- Data Cleaning  
- Data Transformation (ETL)  
- Dashboard Design (Power BI)  
- Exploratory Data Analysis  
- Visual Storytelling  

