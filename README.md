# DE Zoomcamp - Module 6 Homework

This repository contains my solutions for **Module 6 Homework** of the Data Engineering Zoomcamp.

The homework focuses on using **Apache Spark (PySpark)** for batch processing and data analysis.

---

## 🛠 Environment

- Python >= 3.10
- Apache Spark (via PySpark)
- Managed using `uv`
- Running locally (`master("local[*]")`)

---

## 📂 Dataset Used

- Yellow Taxi Trip Data – November 2025  
- Taxi Zone Lookup Table  

Source:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

---

# ✅ Question 1

**Install Spark and PySpark.  
Create a local Spark session and print Spark version.**

**Answer:**
4.1.1

# ✅ Question 2
**Read the November 2025 Yellow dataset.  
Repartition to 4 partitions and save as Parquet.  
What is the average size of the generated Parquet files ?**

**Answer:**
**Average size:** 25 MB


# ✅ Question 3

**How many taxi trips were there on November 15th (pickup date)?**

Trips starting on `2025-11-15`: 

**Answer:**
162,604

# ✅ Question 4

**What is the longest trip duration in hours?**

Maximum trip duration:

**Answer:**
90.6


# ✅ Question 5

**On which port does Spark UI run locally?**

**Answer:**
4040

# ✅ Question 6

**What is the least frequent pickup location zone?**

Using the taxi zone lookup join:

**Answer:**
Governor's Island/Ellis Island/Liberty Island
