# Maji-Ndogo-Analysis


# Maji Ndogo Water Crisis – Data Analysis Project

## 📌 Project Overview
This project explores and analyzes water access challenges in **Maji Ndogo**, a fictional region facing severe water service issues. Using a relational database of over **60,000 records**, the project applies SQL analysis  to uncover patterns, diagnose problems, and recommend solutions.  

The work is divided into **four parts**, each building on the last, moving from raw data exploration to actionable insights.

---

## 📂 Project Parts
| Part | Focus | Link |
|------|-------|------|
| **Part 1 – Data Exploration & Cleaning** | Understanding database structure, previewing tables, identifying anomalies, and correcting data errors. | [View](./Part%201/) |
| **Part 2 – Service Performance Analysis** | Measuring service accessibility, reliability, and coverage; identifying bottlenecks. | [View](./Part%201/) |
| **Part 3 – Quality & Pollution Assessment** | Analyzing water quality data, contamination patterns, and public health risks. | Coming Soon |
| **Part 4 – Insights & Recommendations** | Summarizing findings, visualizing trends, and proposing data-backed interventions. | Coming Soon |

---

## 📊 Dataset
The analysis is based on the **`md_water_servicesb`** MySQL database, which contains **8 tables**:

| Table Name          | Description |
|---------------------|-------------|
| `employee`          | Employee information, roles, and assigned locations |
| `location`          | Geographic coordinates and service area details |
| `visits`            | Field visits, timestamps, and inspection details |
| `water_source`      | Source types, operational status, and location |
| `water_quality`     | Measured water quality ratings |
| `well_pollution`    | Detailed contamination results for wells |
| `global_water_access` | Reference global dataset on water access |
| `data_dictionary`   | Metadata definitions for all fields |

**Size:** 60,000+ rows across multiple relational tables.

---

## 🛠 Methodology & Process
The analysis process combines **SQL querying** with **data storytelling**:

1. **Data Exploration**
   - Previewing all tables with `LIMIT` queries  
   - Understanding schema relationships  
   - Identifying missing values, inconsistencies, and outliers  

2. **Data Cleaning**
   - Correcting mislabeled pollution data  
   - Standardizing inconsistent categorical values  
   - Removing duplicate or irrelevant records  

3. **Data Analysis**
   - Filtering & joining tables to reveal service gaps  
   - Aggregating performance metrics by location and source type  
   - Identifying long wait times and contamination hotspots  

4. **Insights & Reporting**
   - Translating raw results into actionable insights  
   - Structuring findings across four progressive project phases  
   - Presenting clean, reproducible notebooks for review  

---

## 📈 Key Insights 
- **Queue Times** – Shared taps in certain areas have average wait times exceeding 8 hours.  
- **Quality Issues** – Some wells labeled as “Clean” in the water quality table contain **E. coli contamination**.  
- **Coverage Gaps** – Specific rural areas show no functional water points within a reasonable travel distance.  

---

## 💡 Skills Demonstrated
- SQL (data retrieval, joins, aggregation, filtering)
- Data cleaning and anomaly detection
- Multi-step project structuring
- Communicating findings visually and textually
- Using Jupyter Notebook for presentation
- Applying relational database knowledge to solve real-world problems



