# 🚆 Spain Transportation Analytics  

![Dashboard Preview](ضعي_لينك_الصورة_هنا)

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

```text
Origin + " - " + Destination
