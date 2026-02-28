# Vendor Performance Analysis Project 📊

## 📌 Project Overview
In a competitive supply chain environment, monitoring vendor reliability is critical for maintaining operational efficiency and reducing costs. This project develops an end-to-end data pipeline to evaluate vendors based on key performance indicators (KPIs) such as delivery accuracy, lead times, and quality control.

## 🛠 Tech Stack
- **Data Engineering & EDA:** Python (Pandas, NumPy)
- **Database Management:** PostgreSQL
- **Business Intelligence:** Power BI
- **Environment:** Jupyter Notebook, SQL Shell

## 📖 Data Dictionary (Initial)
| Column Name | Description |
| :--- | :--- |
| **Vendor_ID** | Unique identifier for each supplier. |
| **Order_Date** | The date the purchase order was placed. |
| **Delivery_Date** | The actual date the goods were received. |
| **Quantity_Ordered** | The number of units requested from the vendor. |
| **Quantity_Received** | The actual number of units delivered (to check for defects/shortages). |
| **Unit_Price** | The cost per item provided by the vendor. |

## ⚙️ Project Workflow
Based on the defined business problem, the analysis follows a cyclical process to ensure data integrity and insightful reporting:

1. **Problem Definition:** Identifying specific business questions regarding vendor reliability and cost-efficiency.
2. **Data Exploration & Cleaning (Python):** Using Jupyter Notebook to perform EDA, solve research questions, and interpret findings.
3. **Database Integration (SQL):** Loading aggregated tables into PostgreSQL to explore database tables and merge datasets.
4. **Data Visualization (Power BI):** Creating an interactive dashboard to track vendor KPIs and performance trends.
5. **Report Writing:** Finalizing the analysis with a comprehensive report to aid stakeholder decision-making.


   There is 2-3 more dataset file for the project that can't be uploaded because of large size 



## 📂 Repository Structure
- `Vendor_Performance_Cleaning.ipynb`: Python scripts for data cleaning and EDA.
- `Vendor_Analysis_Queries.sql`: SQL scripts for data aggregation and KPI calculation.
- `Vendor_Performance_Dashboard.pbix`: Power BI visualization file.
- `data/`: Folder containing raw and processed datasets.
