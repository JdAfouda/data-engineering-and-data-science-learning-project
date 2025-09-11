# 🌍 ESG Data Engineering Pipeline  

This repository gathers different projects around **ESG (Environmental, Social, Governance) data** applied to sustainable finance.  
The objective is to build a **complete data engineering pipeline**, from **data collection and integration** to **reporting and big data analysis**.  

---

## 📂 Repository Content

### 1. VBA – ESG Indicators Calculation for Portfolios  
- 📑 Files:  
  - `ESG_Portefeuille.xlsm` → Excel workbook with VBA macros for automated calculation of ESG indicators by portfolio.  
  - `ESG_Ptf_DB.csv` → simplified ESG scores database used in the model.  
- ⚙️ Features:  
  - Weighted calculation of portfolio ESG scores.  
  - Automated data import from CSV.  
  - Interactive Excel reporting for analysts.  

---

### 2. Power BI – ESG Scores Reporting & Visualization  
- 📊 Main file: `Reporting et visualisation des scores ESG.pbix`  
- ⚙️ Features:  
  - Interactive dashboards to monitor ESG score evolution.  
  - Sector and portfolio performance visualization.  
  - Dynamic data exploration for top management.  

---

### 3. SQL – ESG Ratings & Carbon Emissions Database  
- 📑 Files:  
  - `duckdb` → lightweight SQL engine to store and query ESG data.  
  - `esg_carbone` → dataset containing ESG scores and CO₂ emissions.  
- ⚙️ Features:  
  - Centralization and normalization of ESG and climate data.  
  - Cleaning and aggregation of raw datasets.  
  - Preparation of inputs for BI analysis.  

---

### 4. Databricks – Large-Scale Processing of Sustainability Data  
- 🔗 Notebook: [Databricks Link](https://dbc-f2770b16-476f.cloud.databricks.com/editor/notebooks/3884327839826267?o=14799125894967#command/5007465019524771)  
- ⚙️ Features:  
  - Big data processing of CSR (Corporate Social Responsibility) and ESG datasets.  
  - Ingestion of structured and unstructured data.  
  - Spark integration for distributed and scalable computation.  

---

## 🚀 Tech Stack
- **Excel VBA** → automation of ESG score calculations.  
- **Power BI** → interactive dashboards and reporting.  
- **SQL (DuckDB)** → ESG data management and querying.  
- **Databricks (PySpark)** → large-scale data processing and integration.  

---

👉 This repository illustrates a **complete ESG data engineering pipeline**, covering **data collection and transformation** (SQL, DuckDB), **automation of calculations** (VBA), and **reporting & big data analysis** (Power BI, Databricks).  
