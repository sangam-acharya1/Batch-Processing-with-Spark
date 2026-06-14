# Batch Processing with Spark

A large-scale batch data processing project built using **Apache Spark (PySpark)** to analyze millions of NYC Taxi trip records efficiently using distributed computing.

---

## Project Overview

This project demonstrates a scalable batch processing workflow using Apache Spark that:

- Processes large NYC Taxi datasets (4M+ records)
- Uses Spark DataFrames for distributed computation
- Reads data from Parquet format for high performance
- Applies data cleaning and transformation at scale
- Optimizes processing using partitioning techniques
- Demonstrates Spark execution and monitoring using Spark UI

---


---

## Tech Stack

- Python
- Apache Spark (PySpark)
- Parquet File Format
- Jupyter Notebook / VS Code

---


---

## Features

### Data Processing
- Loads large-scale NYC Taxi datasets
- Reads Parquet files efficiently
- Applies filtering and transformations using DataFrames

### Performance Optimization
- Uses repartitioning for distributed execution
- Optimizes Spark job execution

### Analytics
- Aggregates trip-level insights
- Handles multi-million record datasets efficiently

### Monitoring
- Uses Spark UI to track:
  - Jobs
  - Stages
  - Task execution

---

## Setup Instructions

### 1. Install Java (Required for Spark)

Spark runs on JVM, so Java is required.

```bash
java -version

