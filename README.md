# End-to-End-Big-Data-Engineering-Pipeline
Scalable E-commerce Data Processing with Hadoop, Spark, and Docker

## Project Overview
This project demonstrates a complete Big Data Pipeline designed to ingest, store, and process large-scale e-commerce datasets. The goal is to transform raw, unstructured data into actionable business insights using the industry-standard "Medallion Architecture" (Bronze, Silver, Gold layers).

## system Architecture
The pipeline follows these stages:

1.Data Ingestion: Raw CSV/JSON datasets are ingested into the system.

2.Data Lake (Storage): Hadoop HDFS acts as the primary storage layer.

3.Batch Processing: Apache Spark (PySpark) performs heavy-duty ETL, cleaning, and aggregation.

4.Data Warehouse/Serving: Processed data is stored in Parquet format or pushed to a PostgreSQL database for reporting.

5.Orchestration: (Optional) Managed via Docker Compose for easy deployment.


 ## Tech Stack
Storage: Hadoop HDFS (Distributed File System)

Processing Engine: Apache Spark 3.x (PySpark)

Environment: Docker & Docker Compose

Language: Python 3.9+

Data Format: Parquet (Optimized for Spark)

📂  **Repository Structure**
