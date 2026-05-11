# End-to-End-Big-Data-Engineering-Pipeline
Scalable E-commerce Data Processing with Hadoop, Spark, and Docker

## Project Overview
This project demonstrates a complete Big Data Pipeline designed to ingest, store, and process large-scale e-commerce datasets. The goal is to transform raw, unstructured data into actionable business insights using the industry-standard "Medallion Architecture" (Bronze, Silver, Gold layers).

🏗System Architecture
The pipeline follows these stages:

Data Ingestion: Raw CSV/JSON datasets are ingested into the system.

Data Lake (Storage): Hadoop HDFS acts as the primary storage layer.

Batch Processing: Apache Spark (PySpark) performs heavy-duty ETL, cleaning, and aggregation.

Data Warehouse/Serving: Processed data is stored in Parquet format or pushed to a PostgreSQL database for reporting.

Orchestration: (Optional) Managed via Docker Compose for easy deployment.
