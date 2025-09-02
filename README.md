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
| **Part 2 – Service Performance Analysis** | Measuring service accessibility, reliability, and coverage; identifying bottlenecks. | [View](Part_2) |
| **Part 3 – Quality & Pollution Assessment** | Analyzing water quality data, contamination patterns, and public health risks. | [View](Part_3) |
| **Part 4 – Insights & Recommendations** | Summarizing findings, visualizing trends, and proposing data-backed interventions. |[View](Part_4)|

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

## 🔑 Key Insights  

Our analysis uncovered critical insights into Maji Ndogo’s water crisis:  

- **Access & Usage**
  - 43% of citizens rely on **shared taps**, with ~2,000 people often sharing a single tap.  
  - 31% have taps at home, but **45% are non-functional**, especially in towns like **Amina, rural Amanzi, Akatsi, and Hawassa**.  
  - 18% use **wells**, yet only **28% are clean**, concentrated in **Hawassa, Kilimani, and Akatsi**.  
  - The majority of sources are **rural**, highlighting infrastructure gaps outside urban centers.  

- **Queue Times**
  - Average wait times exceed **120 minutes**, peaking on **Saturdays, mornings, and evenings**.  
  - In extreme cases, some shared taps showed wait times of **8+ hours**.  

- **Water Quality Issues**
  - Some wells marked as *“Clean”* were found to contain **E. coli contamination**, revealing critical data quality problems.  
  - Discrepancies between field surveyor scores and auditor reports highlight the need for **systematic auditing and training**.  
  - Certain employees consistently reported inaccurate results, suggesting **training gaps or malpractice risks**.  

- **Data-Driven Improvements**
  - By using **CTEs and views**, we built a systematic auditing process to validate survey data.  
  - These steps ensured that **water quality assessments are accurate and verifiable**, directly protecting **public health**.  

---

## 🛠 A Practical Plan  

Based on the findings, we transitioned from analysis to **clear, actionable steps**:  

1. **Shared Taps** – Prioritize repairs and expansion in towns like **Bello, Abidjan, and Zuri** to reduce queues to under **30 minutes**, in line with **UN standards**.  
2. **Wells** – Install **RO filters** for chemical contamination and **UV + RO filters** for biological contamination, while investigating long-term pollution causes.  
3. **Infrastructure Repairs** – Restore broken systems in towns like **Amina, Lusaka, Zuri, Djenne, and rural Amanzi**, providing immediate impact to thousands.  
4. **Short-Term Relief** – Deploy **water trucks to river-dependent areas**, beginning with **Sokoto**, while drilling wells for sustainable solutions.  
5. **Long-Term Strategy** – Expand home tap access where feasible, but focus resources first on **high-impact, scalable interventions**.  

---

## 💡 Skills Demonstrated
- SQL (data retrieval, joins, aggregation, filtering)
- Data cleaning and anomaly detection
- Multi-step project structuring
- Communicating findings visually and textually
- Using Jupyter Notebook for presentation
- Applying relational database knowledge to solve real-world problems



