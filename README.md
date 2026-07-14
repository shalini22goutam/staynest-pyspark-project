# StayNest - PySpark Deep Dive Assignment

A hands-on PySpark assignment covering the core DataFrame APIs, Spark SQL, window functions, joins, and writing data in Parquet and Delta formats.

Assignment walkthrough link : https://drive.google.com/drive/folders/18Y1uYlN1mrlzrxd6-vVsJuqG1Yl2RrTb?usp=sharing

## Overview

This notebook demonstrates fundamental PySpark transformations and actions using a hotel booking dataset. The exercises are designed to build practical experience with distributed data processing in Apache Spark.

## Dataset

The assignment uses three CSV files:

- `bookings.csv`
- `hotels.csv`
- `customers.csv`

These datasets represent hotel bookings, hotel information, and customer details.

## Topics Covered

### Task 1 – Read and Inspect Data
- Read CSV files
- Infer schema
- Display schema
- Preview records
- Generate summary statistics

### Task 2 – Select and Filter
- Select required columns
- Filter records using multiple conditions
- Use `col()` expressions

### Task 3 – Derived Columns
- Create calculated columns
- Apply conditional logic using `when()`
- Extract month from dates

### Task 4 – Aggregations
- Group data
- Calculate:
  - Total revenue
  - Average booking amount
  - Maximum booking value
  - Booking count
  - Distinct customer count

### Task 5 – Joins
- Inner Join
- Left Join
- Left Anti Join
- Multi-table joins

### Task 6 – Spark SQL & Window Functions
- Register temporary views
- Execute Spark SQL queries
- Rank hotels using Window Functions
- Retrieve Top-N records per city

### Task 7 – Data Output
- Write data as Parquet
- Save data as Delta Table
- Read Delta table for verification

### Task 8 – End-to-End Data Pipeline
A fully chained DataFrame pipeline combining:
- Filtering
- Joining
- Aggregation
- Sorting
- Final reporting

---

## Technologies Used

- Python
- Apache Spark (PySpark)
- Spark SQL
- Delta Lake
- Databricks

---

## Skills Demonstrated

- DataFrame transformations
- Filtering and projection
- Aggregations
- Window functions
- SQL on Spark
- Data joins
- Parquet and Delta storage
- Method chaining
- Distributed data processing

---

## Project Structure

```
StayNest_S06_assignment_notebook.ipynb
README.md
```

---

## How to Run

1. Upload the CSV datasets to your Databricks Volume.
2. Update the `BASE` path inside the notebook.
3. Execute the notebook sequentially from Task 1 to Task 8.
4. Verify the generated Parquet files and Delta table.

---

## Author

**Shalini Goutam**

