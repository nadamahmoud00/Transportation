# 🚆 Spain Transportation Analytics Dashboard  

<p align="center">
  <img src="https://github.com/nadamahmoud00/Transportation/blob/main/power%20bi.PNG" width="100%">
</p>

 
## 📌 Project Overview  

Spain Transportation Analytics is an end-to-end Business Intelligence project designed to analyze transportation operations across Spain using modern Data Engineering and Analytics tools.  

The project focuses on transforming raw transportation datasets collected from multiple Excel and CSV files into a clean, structured, and interactive analytical dashboard.  

---

# 🎯 Business Objectives  

- Build a centralized transportation dataset from multiple raw sources  
- Perform data cleaning and preprocessing  
- Handle missing values, duplicates, and inconsistent records  
- Generate business KPIs and operational insights  
- Create an interactive dashboard for transportation analytics  

---

# 📂 Dataset Description  

The dataset contains transportation trip information including:  

| Category | Description |
|---|---|
| 🚆 Train Information | Train Type & Train Class |
| 📍 Routes | Origin & Destination Stations |
| 💰 Financial Data | Ticket Fare & Revenue |
| ⏰ Time Analysis | Departure & Arrival Time |
| 👥 Passenger Data | Passenger Records & Trips |

### 📁 Data Sources  

- Excel Files (.xlsx)  
- CSV Files (.csv)  

---

# ⚙️ ETL & Data Preparation  

## 🔹 Data Engineering Using SSIS  


✔️ Extracting data from multiple source files  

✔️ Building Data Flow Tasks  

✔️ Error handling and invalid record management  

✔️ Ignoring null and corrupted records  

✔️ Splitting and transforming columns  

✔️ Merging and integrating datasets  

✔️ Loading cleaned data into the analytical model  

---

## 🔹 Data Transformation Using Power Query  


### 🛠️ Data Cleaning Processes  

- Removed duplicate records  
- Fixed inconsistent values  
- Handled missing values  
- Standardized data types  
- Cleaned fare values  
- Standardized train categories  

---

## ➕ Custom Feature Engineering  

A new calculated column was created to combine route information:  

```text
Origin + " - " + Destination
```

### Example  

```text
Madrid - Barcelona
```

---

# 📊 Dashboard KPIs  

| KPI | Value |
|---|---|
| 🚆 Total Trips | 2.57M |
| 👥 Total Passengers | 2.57M |
| 💰 Total Revenue | $143.83M |

---

# 📈 Analytical Insights  

## 💰 Revenue Insights  

- AVE train type generated the highest revenue  
- Revenue peaks during daytime operational hours  

---

## 🚉 Route Performance  

### Top Performing Routes  

1. Madrid → Barcelona  
2. Madrid → Sevilla  
3. Barcelona → Madrid  

---

## 🎟️ Fare Distribution Analysis  

The majority of passengers selected:  

- Promo Fare  
- Flexible Fare  

---

## 🚆 Passenger Class Analysis  

Most passengers preferred:  

- Turista Class  

---

# 🖥️ Dashboard Features  

The dashboard includes:  

✅ Interactive Slicers & Filters  

✅ Passenger Trend Analysis  

✅ Revenue Analysis  

✅ Route Distribution Visualization  

✅ Train Class Distribution  

✅ Fare Distribution Analysis  

✅ Time-Based Operational Insights  

---

# 🛠️ Tools & Technologies  

| Tool | Purpose |
|---|---|
| SSIS | ETL & Data Integration |
| Power Query | Data Cleaning & Transformation |
| Power BI | Dashboard Development & Visualization |
| Excel / CSV | Raw Data Sources |

---

# 🚀 Skills Demonstrated  

- ETL Pipeline Development  
- Data Cleaning & Transformation  
- Data Modeling  
- Dashboard Design  
- Business Intelligence Analytics  
- KPI Reporting  
- Data Visualization  
- Insight Generation  

---

# 📌 Dashboard Preview  

The dashboard provides a complete transportation analytics experience through:  

- KPI Cards  
- Revenue Visualizations  
- Passenger Trend Monitoring  
- Route Analysis  
- Fare Distribution Charts  
- Train Class Insights  
- Interactive Dashboard Filters  

---

# ✅ Conclusion  

This project demonstrates a complete Business Intelligence workflow starting from raw transportation datasets to a fully interactive analytical dashboard.  

The solution enables stakeholders to:  

- Understand passenger behavior  
- Identify high-demand routes  
- Analyze revenue performance  
- Monitor transportation operations across Spain  

The project highlights practical experience in Data Engineering, ETL development, data transformation, and Business Intelligence visualization.




