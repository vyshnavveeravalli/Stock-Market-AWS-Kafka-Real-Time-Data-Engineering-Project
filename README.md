# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka

**Key Components and Functionality**

**Data Sources:**
**Real-time APIs:** Integrate with real-time stock market data APIs (e.g., Alpha Vantage, IEX Cloud) to retrieve market data.
**Web Scraping:** Extract data from financial websites or news sources using web scraping techniques.
**Kafka Producer:** Send data to a Kafka topic in a distributed and scalable manner.
**Kafka Consumer:** Consume data from the Kafka topic and perform data processing tasks.

**Data Processing:**
**Data Cleaning**: Handle missing values, outliers, and inconsistencies in the data.
**Data Transformation**: Convert data to a suitable format for analysis (e.g., JSON, CSV).
**Feature Engineering**: Create new features based on existing data (e.g., technical indicators).

**Data Storage**:
**Time Series Database**: Store time-series data in a specialized database (e.g., InfluxDB, TimescaleDB) for efficient querying.
**Data Warehouse**: Load processed data into a data warehouse (e.g., Redshift, BigQuery) for batch processing and analysis.


