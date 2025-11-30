# US Household Income Data Project — SQL Data Cleaning & Exploration

This repository contains a complete **end-to-end SQL project** analyzing **US Household Income** data. It is divided into two structured SQL scripts:

- **Part 1: Data Cleaning**
- **Part 2: Data Exploration & Analysis**

The goal of this project is to demonstrate real-world data cleaning, transformation, and exploratory analysis techniques using SQL.

---
## 📌 **Project Overview**
This project works with two tables:
- `us_household_income`
- `us_household_income_statistics`

Across both scripts, you will:
- Clean, standardize, and validate raw data
- Remove duplicates
- Correct inconsistent values
- Explore income patterns across states, cities, and community types
- Join datasets to uncover deeper insights

---
## 📁 **Repository Contents**
### **1. Data Cleaning Script** (`US Household Income Data Cleaning.sql`)
Key tasks performed:
- Renamed incorrect column names
- Checked record counts for consistency
- Detected and removed duplicate records using **window functions**
- Standardized state names (e.g., *alabama → Alabama*, *georia → Georgia*)
- Fixed inconsistent values in the `Type` column (e.g., *Boroughs → Borough*)
- Identified blank, null, or zero values in land and water area fields
- Corrected blank entries using existing data in the dataset

### **2. Data Exploration Script** (`US Household Income Data Exploration.sql`)
Core analytical steps:
- Explored land and water area across states and cities
- Ranked states by total land and water size
- Joined income and statistics tables on `id` to enrich analysis
- Calculated state-wise **average mean** and **median income**
- Identified top 10 earning states
- Computed income distribution by community `Type`
- Investigated community types with lowest average income
- Analyzed income patterns at **city-level granularity**

---
## 🛠️ **Technologies Used**
- **SQL** (MySQL / PostgreSQL compatible)
- Window Functions
- Grouping, Filtering, Joining
- Aggregation techniques

---
## 📊 **Insights You Can Derive**
✔ State-wise income comparison (Mean vs Median)  
✔ City-level income distribution  
✔ Community-type income disparities  
✔ Impact of location (State, County, City) on household income  
✔ Land vs water area comparisons across states

(You can customize this section if you'd like the exact insights from your output.)

---
## 🚀 How to Run the SQL Scripts
1. Import both tables (`us_household_income` and `us_household_income_statistics`) into your SQL database.  
2. Run the **Data Cleaning** script **first** to fix inconsistencies.  
3. Run the **Data Exploration** script to generate insights.  
4. Modify queries as needed to extend the analysis.

---
## 📌 **Future Enhancements**
- Build a **Tableau / Power BI dashboard** using the cleaned dataset
- Add geo-visualizations (state/county-level heatmaps)
- Export final tables for machine learning analysis
- Connect analysis with US Census or public demographic datasets

---
## 🤝 **Contributing**
Feel free to contribute improvements or additional analytical queries.

---
## 📜 **License**
This project is open-source under the MIT License.

---
If you want, I can also:
- Create a **requirements.txt** (if you add Python later)
- Design a **Power BI dashboard layout** for this dataset
- Add a **data dictionary** for both tables
