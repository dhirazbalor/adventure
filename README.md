## 📊 Project Overview

This project implements a real-time data pipeline using Microsoft Azure services:

- **Azure Data Factory** ingests data from web APIs into **ADLS Gen2 (Bronze)**.
- **Azure Databricks** transforms data using **Apache Spark**, storing results in the **Silver layer**.
- Aggregated data is saved in the **Gold layer** and queried via **Azure Synapse Serverless SQL**.
- **Power BI** connects to Synapse for dynamic dashboards and business insights.

The pipeline follows a modern **Lakehouse architecture**: Bronze → Silver → Gold.
