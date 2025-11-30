# NYC Traffic Collision Analysis  
### A Data ETL, Exploratory Analysis, and Public Safety Insights Project  
**Author:** Akhila Korlapati  
**Tools Used:** Python, Pandas, GeoPandas, Seaborn, Plotly, Folium, Tableau  
**Dataset:** NYC Motor Vehicle Collisions (NYC Open Data, Dataset ID: *h9gi-nx95*)

---

## 📌 Overview

This repository contains my end-to-end analysis of the **NYC Motor Vehicle Collisions** dataset.  
The goal of this project is to identify **temporal, spatial, and severity-based patterns** in collisions across New York City and to derive insights relevant to **public safety, policy evaluation, and investigative work**.

The project includes:

- Large-scale **data ingestion and ETL** (via NYC Open Data API)  
- **Data cleaning** and normalization of timestamps, boroughs, and geographic fields  
- **Temporal pattern analysis** (hour, day, month, year)  
- **Severity modeling** (injuries + fatalities)  
- **Geospatial and borough-level insights**  
- **Interactive Tableau dashboard** highlighting key crash trends  

This notebook demonstrates my ability to work with complex, real-world public datasets—skills that directly align with investigative and analytical roles in public-sector agencies such as the New York State Attorney General’s Office.

---

## 📊 Key Capabilities Demonstrated

### **1. Data Engineering / ETL**
- Automated download of NYC collision data  
- Flexible parsing of mixed-format timestamps  
- Extraction of temporal features (hour, weekday, month, year)  
- Standardization of categorical geographic fields  

### **2. Exploratory Data Analysis**
- Crash trends across years, months, days, and hours  
- Severity modeling using injuries + fatalities  
- High-risk time windows (late evenings and peak commuting hours)  
- Borough-level comparison of crash counts and severity  

### **3. Advanced Visualization**
- Day × hour heatmaps for crash frequency and severity  
- Borough distribution analysis  
- Crash–injury temporal correlation  
- Maps and time-series visualizations in the notebook  
- Tableau dashboard for interactive exploration  

### **4. Public-Safety & Investigative Insights**
- Identification of high-risk collision windows  
- Severity hotspots  
- Borough disparities relevant for transportation policy  
- Data-driven interpretation suited for investigative and regulatory work  

---
```text
## 📁 Repository Structure

│
├── NYC_Project.ipynb
├── README.md # Project documentation


_No datasets or images are stored in this repository.  
The notebook dynamically downloads and processes data from NYC Open Data._

---

## 📊 Tableau Dashboard

Interactive dashboard:  
**https://public.tableau.com/views/NYCTrafficCollisions_17618732468110/NYCTrafficAnalysisDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

The dashboard visualizes NYC crash patterns, including:

- Crash severity map (injuries + fatalities)  
- Crash vs. injury trends (2012–2025)  
- Day × hour heatmap showing high-risk time windows  
- Borough-level crash distribution  
- KPIs for total crashes, injuries, and fatalities  

These visuals reveal critical collision patterns that can support public-safety planning and data-informed decision-making.

---

## Contact  
If you have any questions about the analysis or implementation, feel free to reach out.

**Email:** akorl@uis.edu
