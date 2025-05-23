# Reddit Data Engineering Pipeline

A comprehensive data pipeline using **Reddit API**, **Apache Airflow**, **Celery**, **PostgreSQL**, **Amazon S3**, **AWS Glue**, **Amazon Athena**, and **Amazon Redshift**.

This project demonstrates a robust ETL (Extract, Transform, Load) solution to extract Reddit data and load it into an Amazon Redshift data warehouse for analytics and reporting.

## Overview

The pipeline is designed to:

- **Extract** data from Reddit using its API.
- **Store** the raw data into an S3 bucket from Airflow.
- **Transform** the data using AWS Glue and Amazon Athena.
- **Load** the transformed data into Amazon Redshift for analytics and querying.

## Tech Stack

- **Reddit API**: Source of the data.
- **Apache Airflow & Celery**: Orchestrates the ETL process and manages task distribution.
- **PostgreSQL**: Temporary storage and metadata management.
- **Amazon S3**: Raw data storage.
- **AWS Glue**: Data cataloging and ETL jobs.
- **Amazon Athena**: SQL-based data transformation.
- **Amazon Redshift**: Data warehousing and analytics.
- **Docker**: Containerizes the Airflow webserver and other services for a consistent development and production environment.
- **Power BI**: Data visualization tool to generate insights from the processed data.


## Architecture Diagram
![Architecture Diagram](https://github.com/user-attachments/assets/7cefc1a0-78a5-4185-858c-ef1e876f33fa)


