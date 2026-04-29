# Pyspark

# PySpark Complete Hands-On Course

A complete practical journey to learn PySpark for Data Engineering using Databricks.

This repository covers PySpark from basic DataFrame operations to advanced ETL concepts used in real-world Data Engineering projects.

---

# Course Objective

The goal of this course is to learn:

* PySpark hands-on from beginner to advanced
* Real-world Data Engineering transformations
* DataFrame operations used in industry
* SQL functions and ETL logic
* Aggregations, Joins, and Window Functions
* File handling using CSV, JSON, and Parquet
* Performance optimization concepts
* Real project use cases like SCD, Incremental Load, CDC, and Deduplication

This course is focused on practical coding in Databricks notebooks.

---

# Tools Used

* Python
* PySpark
* Apache Spark
* Databricks
* SQL
* Parquet


---

# Course Modules

---

## Module 1: Setup + First Code

Topics Covered:

* What is PySpark
* Where to write PySpark code
* Using Databricks for PySpark
* SparkSession basics
* createDataFrame()
* show()
* printSchema()
* columns
* dtypes

Practice:
Creating first employee DataFrame and understanding DataFrame structure.

---

## Module 2: DataFrame Basics

Topics Covered:

* select()
* filter()
* where()
* withColumn()
* drop()
* withColumnRenamed()
* distinct()
* dropDuplicates()
* orderBy()
* limit()

Practice:
Filtering employees, adding tax/bonus columns, sorting salary, removing duplicates.

---

## Module 3: SQL Functions

Topics Covered:

* col()
* lit()
* when()
* concat()
* substring()
* upper()
* lower()
* trim()
* current_date()

Practice:
Creating fixed columns, salary status, uppercase transformations, string operations, ETL-style transformations.

---

## Module 4: Aggregations

Topics Covered:

* groupBy()
* agg()
* sum()
* avg()
* count()
* max()
* min()

Practice:
Department-wise salary analysis and reporting.

---

## Module 5: Joins

Topics Covered:

* Inner Join
* Left Join
* Right Join
* Full Join
* Left Semi Join
* Left Anti Join
* Self Join

Practice:
Customer-order joins and dimension-fact joins.

---

## Module 6: Window Functions

Topics Covered:

* row_number()
* rank()
* dense_rank()
* lead()
* lag()
* running total

Practice:
Employee ranking, latest records, transaction history analysis.

---

## Module 7: Advanced PySpark

Topics Covered:

* UDF
* repartition()
* coalesce()
* cache()
* persist()
* broadcast join
* skew handling
* salting

Practice:
Performance optimization and large-scale transformation handling.

---

## Module 8: File Handling

Topics Covered:

* Read CSV
* Read JSON
* Read Parquet
* Write CSV
* Write Parquet
* Partitioned Write

Practice:
Real file ingestion and export pipeline.

---

## Module 9: Real Data Engineering Use Cases

Topics Covered:

* Incremental Load
* SCD Type 1
* SCD Type 2
* Deduplication
* CDC Logic
* ETL Mini Project







