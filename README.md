# Ingest-data-with-a-pipeline-in-Microsoft-Fabric
This project demonstrates how to implement a data ingestion pipeline in Microsoft Fabric, combining pipeline activities with Apache Spark notebooks to extract, transform, and load (ETL) data into a lakehouse.
<img width="908" alt="image" src="https://github.com/user-attachments/assets/dad8373f-6fef-4e94-9c60-40de0085b82a" />

#  Microsoft Fabric Lakehouse Ingestion Project

## 🔍 Project Overview

This project demonstrates how to build a complete **data ingestion and transformation pipeline** in **Microsoft Fabric** using Lakehouses, Pipelines, and Notebooks.

We ingest sales data from an external HTTP source into a **Lakehouse**, process it using **Apache Spark**, and store it in a structured Delta table for analytical purposes. It is designed as a practical, hands-on lab suitable for data engineers learning to implement ETL/ELT workflows in Microsoft Fabric.

---

##  Tools & Technologies

- [Microsoft Fabric](https://app.fabric.microsoft.com/)
- Apache Spark (via Fabric Notebooks)
- Pipelines (Copy Data, Delete Data, Notebook Activities)
- Delta Lake
- PySpark

---

##  Features Implemented

-  Created a Fabric **Workspace**
-  Built a **Lakehouse** for storing and querying data
-  Created a **Pipeline** with:
  - `Copy Data` activity to ingest external CSV
  - `Delete Data` activity to remove stale data
  - `Notebook` activity to transform data
-  Developed a **Spark Notebook** to:
  - Parse and clean data
  - Add new columns: `Year`, `Month`, `FirstName`, `LastName`
  - Store data in a Delta table (`new_sales`)
-  Used **parameterization** in notebooks for reusability

---


