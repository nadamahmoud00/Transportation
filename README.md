# 🚆 Spain Transportation Analytics  
(https://github.com/nadamahmoud00/Transportation/blob/main/power%20bi.PNG))

---

# 📌 Project Overview  

Spain Transportation Analytics is a Business Intelligence project that analyzes transportation data in Spain using an end-to-end Data Engineering workflow.  

The project was developed using:  

- :contentReference[oaicite:0]{index=0}  
- :contentReference[oaicite:1]{index=1}  
- :contentReference[oaicite:2]{index=2}  

The goal of the project is to transform raw transportation datasets from multiple Excel and CSV files into a clean, structured, and interactive analytical dashboard.  

---

# 🎯 Project Objectives  

✔️ Build a clean transportation dataset from multiple raw files  

✔️ Perform data preprocessing and transformation  

✔️ Handle missing values, duplicates, and data quality issues  

✔️ Create meaningful KPIs and business insights  

✔️ Design an interactive dashboard for transportation analytics  

---

# 📂 Dataset Information  

The dataset contains transportation trip information such as:  

- 🚉 Train Type  
- 🎟️ Train Class  
- 📍 Origin Station  
- 📍 Destination Station  
- 💰 Ticket Fare  
- ⏰ Departure Time  
- ⏰ Arrival Time  
- 👥 Passenger Information  
- 💵 Revenue Data  

## 📁 Data Sources  

- Excel Files (.xlsx)  
- CSV Files (.csv)  

---

# ⚙️ ETL & Data Cleaning Process  

## 🔹 Using SSIS  

Inside :contentReference[oaicite:3]{index=3} we performed:  

- Data Extraction from multiple source files  
- Data Flow Tasks  
- Error Handling  
- Ignoring invalid or null records  
- Splitting and transforming columns  
- Merging and integrating datasets  
- Loading the cleaned data into the final model  

---

## 🔹 Using Power Query  

Inside :contentReference[oaicite:4]{index=4} we performed:  

### 🛠️ Data Transformations  

- Removed duplicates  
- Fixed inconsistent values  
- Handled missing data  
- Changed data types  
- Cleaned fare values  
- Standardized train categories  

---

## ➕ Created Custom Column  

A new route column was created using:  


Origin + " - " + Destination
Madrid - Barcelon


📊 Dashboard KPIs

🔹 Main KPIs

KPI	Value

🚆 Total Trips	2.57M
👥 Total Passengers	2.57M
💰 Total Revenue	$143.83M
📈 Dashboard Insights
💰 Revenue Analysis

AVE train type generated the highest revenue
Most revenue occurs during peak daytime hours

🚉 Route Analysis
🔥 Top Routes
Madrid → Barcelona
Madrid → Sevilla
Barcelona → Madrid
🎟️ Fare Distribution

Most passengers selected:

Promo Fare
Flexible Fare
🚆 Train Class Analysis

The majority of passengers preferred:

Turista Class

🖥️ Dashboard Features


# The dashboard includes:

✅ Interactive Filters (Slicers)

✅ Revenue Analysis

✅ Passenger Trends

✅ Route Distribution

✅ Train Class Distribution

✅ Fare Analysis

✅ Time-Based Analysis

---


#🛠️ Tools & Technologies

Tool	Purpose
SSIS	ETL Process
Power Query	Data Cleaning & Transformation
Power BI	Dashboard & Visualization
Excel / CSV	Raw Data Sources


---
🚀 Key Skills Demonstrated

ETL Pipelines
Data Cleaning
Data Transformation
Data Modeling
Dashboard Design
Business Intelligence
Data Visualization
KPI Analysis


---
📌 Dashboard Preview

The dashboard provides a complete transportation analytics experience through:

KPI Cards
Revenue Charts
Passenger Trends
Route Distribution
Fare Analysis
Train Class Insights
Interactive Slicers

---

Conclusion

This project demonstrates a complete Business Intelligence workflow starting from raw transportation datasets to an interactive analytical dashboard.

The analysis helps identify:

Passenger behavior
High-demand routes
Revenue trends
Train performance across Spain

The project highlights practical skills in Data Engineering, ETL processes, Data Transformation, and Business Intelligence visualization.










