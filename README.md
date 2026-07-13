# Data Management Assignment 2
## Apache Spark and Cassandra Integration with MovieLens Dataset

## Student Information
- **Name:** Mohd Sahfri bin Ab Aziz (P146220)
- **Course:** STQD6324 Data Management
- **University:** Faculty Science & Technology, Universiti Kebangsaan Malaysia (UKM)

---

## Project Overview

This project demonstrates the integration of Apache Spark and Apache Cassandra for large-scale data processing using the MovieLens 100K dataset.

The notebook covers the complete big data analytics workflow, including data loading, preprocessing, distributed processing, SQL analysis, Cassandra storage, and data visualization.

---

### Software Environment
|     Component	                         |         Version                 |
|----------------------------------------|---------------------------------|
| Operating System	                     | Ubuntu Linux (Docker Container) |
| Apache Spark	2.3.0.2.6.5.0-292        |                                 |
| Scala	                                 |    2.11.8                       |    | Java	                                 |  OpenJDK 1.8.0_171              |
| Apache Cassandra                       |	3.11.16                        |
| Python (Docker Notebook)               |	3.6                            |
| Python (HDP Sandbox)                   |	2.7.5                          |
| Jupyter Notebook	                     | Docker-based Notebook           |
| Hadoop Distribution	                 |Hortonworks Data Platform (HDP) 2.6.5|
| Dataset	                             | MovieLens 100K                  |
---

## Python Libraries


|Library                   | 	Purpose                            |
|--------------------------|---------------------------------------|
| pyspark.sql              |	Create Spark DataFrames            |
| SparkSession	           | Initialize Apache Spark               |
| Row                      |	Create structured rows from RDDs   |
| pyspark.sql.functions    |	Data transformation and aggregation|
| pyspark.sql.types        |	Define DataFrame schemas           |
| os                       |	File and directory management      |
| glob                     |	Locate exported Spark files        |
| shutil                   |	Copy and organize exported files   |
| pandas	               |Convert Spark DataFrames for visualization|
|matplotlib                |	Generate charts and graphs         |
---

## Dataset

MovieLens 100K Dataset

- 100,000 movie ratings
- 943 users
- 1,682 movies

---

## Technical Requirements Completed

- Import required libraries
- Load MovieLens dataset into HDFS
- Create Spark RDDs
- Convert RDDs to Spark DataFrames
- Clean and preprocess data
- Execute Spark SQL queries
- Store processed data in Cassandra
- Read Cassandra tables into Spark
- Visualize analytical results

---

## Project Structure

```text
📘 Data Management Assignment
│
├── Introduction
├── Objectives
├── Technical Requirements
├── Environment Setup
│
├── Import Libraries
├── Spark Session
├── Load MovieLens Dataset
├── Create RDDs
├── Convert to DataFrames
├── Data Cleaning
├── Join DataFrames
│
├── Spark SQL Analysis
│     ├── Question (i)
│     ├── Question (ii)
│     ├── Question (iii)
│     ├── Question (iv)
│     └── Question (v)
│
├── Cassandra Integration
├── Read from Cassandra
├── Data Visualizations
├── Discussion
├── Conclusion
└── References
```
## Author

Mohd Sahfri bin Ab Aziz

Master of Science (Executive)-(Data Science and Analytics)

Universiti Kebangsaan Malaysia
