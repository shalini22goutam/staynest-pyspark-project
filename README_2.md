# StayNest Assignments – PySpark & Delta Lake

## Overview
This repository contains assignments completed using **PySpark** on **Databricks**. The notebooks cover Spark DataFrame operations, Spark SQL, Delta Lake features, and the Medallion Architecture.

Assignment walkthrough link : https://drive.google.com/drive/folders/18Y1uYlN1mrlzrxd6-vVsJuqG1Yl2RrTb?usp=sharing

## Dataset

The assignment uses three CSV files:

- `bookings.csv`
- `hotels.csv`
- `customers.csv`

These datasets represent hotel bookings, hotel information, and customer details.

## Technologies
- PySpark
- Spark SQL
- Delta Lake
- Databricks

## Assignments

### Session  – PySpark
- DataFrame transformations
- Filtering and aggregations
- Joins
- Window functions
- Spark SQL
- Writing DataFrames
- End-to-end data pipeline

### Session  – Delta Lake
- Broadcast joins
- Delta tables and transaction history
- Time Travel & RESTORE
- OPTIMIZE & ZORDER
- Bronze, Silver & Gold layers
- Incremental loading using MERGE

## Repository Structure
```
.
├── StayNest_S06_assignment_notebook.ipynb
├── StayNest_S07_assignment_notebook.ipynb
├── README.md

```

## How to Run

1. Upload the CSV datasets to your Databricks Volume.
2. Update the `BASE` path inside the notebook.
3. Execute the notebook sequentially.
4. Verify the generated Parquet files and Delta table.

## Key Learnings
- PySpark DataFrame APIs
- Spark SQL and window functions
- Delta Lake versioning and optimization
- Medallion Architecture
- Incremental ETL with MERGE

---
**Author:** Shalini Goutam
