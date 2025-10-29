# End-to-End Data Pipeline using Azure Databricks and Earthquake API

## Overview
This project demonstrates an end-to-end data engineering pipeline built on Azure Databricks, following the Medallion Architecture (Bronze, Silver, Gold).  The pipeline ingests real-time earthquake data from the USGS API, processes it using PySpark, and stores raw and processed data in Azure Blob Storage for analytics and visualization in Power BI (Future Work).

## Components
1. Earthquake API  
2. Bronze Layer: Raw data ingestion using PySpark, stored in Azure Blob Storage  
3. Silver Layer: Data cleaning and transformation  
4. Gold Layer: Aggregation and enrichment for analytics  
5. Power BI: Visualization and insights (Future Work)

## Workflow Automation
- Implemented Databricks Workflows to orchestrate dependencies between notebooks  
- Configured job scheduling for daily ingestion and transformation  
- Verified data quality and lineage across all layers  

## Tech Stack
Data Engineering: Azure Databricks, PySpark, Delta Lake  
Cloud & Storage: Azure Blob Storage, REST API Integration  
Visualization: Power BI  
Programming: Python, SQL  
Tools: Git, GitHub, Databricks Notebooks, VS Code  

## Key Highlights
- Built a scalable and automated ETL pipeline from API to analytics  
- Followed Medallion Architecture (Bronze, Silver, Gold)  
- Used Azure Blob Storage to store raw and processed data  
- Ensured data consistency, quality, and workflow automation  
- Prepared foundation for real-time analytics and Power BI dashboards  

## Future Enhancements
- Integrate Power BI dashboard with Gold layer data  
- Add Spark Structured Streaming for near real-time ingestion  
- Implement data validation and monitoring framework  

