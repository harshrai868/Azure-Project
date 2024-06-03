# Healthcare Data Pipeline Project

## Overview

In this project we implement a data pipeline using Azure services for analyzing a synthetic healthcare dataset. The pipeline involves data ingestion, storage in Azure Data Lake Storage Gen2 (ADLS), data cleaning using PySpark in Azure Data Factory (ADF), analytics in Synapse Analytics, and visualization in Power BI.

## Dataset

### Description

The dataset contains synthetic patient healthcare records, including demographic information, medical conditions, admission details, billing amounts, medications, and test results. It's suitable for various data analysis and modeling tasks in the healthcare domain.

### Schema

The dataset schema includes the following columns:

- Name
- Age
- Gender
- Blood Type
- Medical Condition
- Date of Admission
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Room Number
- Admission Type
- Discharge Date
- Medication
- Test Results

## Architectural Diagram

![Architectural Diagram](https://github.com/harshrai868/Azure-Project/blob/main/AD.jpg?raw=true)

- **Azure Data Factory (ADF):** Orchestrates data movement and transformations.
- **Azure Data Lake Storage Gen2 (ADLS):** Stores raw and transformed data.
- **Synapse Analytics:** Performs data analysis using SQL queries.
- **Power BI:** Creates interactive dashboards for data visualization.

## Data Pipeline Creation

### Data Ingestion

Data is ingested using Azure Data Factory (ADF) from the chosen source format (e.g., CSV). ADF supports various connectors for data sources, and the copy activity method is used for ingestion.

### Data Storage

The ingested data is stored in Azure Data Lake Storage Gen2 (ADLS), providing scalability and flexibility for various data formats.

### Data Transformation (PySpark)

PySpark scripts are executed within Azure Data Factory (ADF) for data cleaning tasks, including handling missing values, correcting inconsistencies, and feature engineering.

## Transformation and Analytics

### PySpark for Cleaning

PySpark code within ADF is utilized to clean the ingested data based on observations, ensuring data quality and accuracy.

### Transfer to Synapse

Cleaned data is transferred from ADLS to Synapse Analytics using ADF, enabling data analysis using SQL queries.

### Synapse Analytics

Synapse Analytics is used for performing data analysis, exploring data trends, identifying patterns, and uncovering insights.

## Visualization and Power BI

The analysis results are visualized using Power BI, creating interactive dashboards with charts and graphs for sharing insights and facilitating data-driven decision-making.

## Here are some visualizations created in Power BI

![Power BI Dashboard 1](https://github.com/harshrai868/Azure-Project/blob/main/Dashboard.jpeg?raw=true)


## Conclusion

Implementing a data pipeline using Azure services offers several advantages for organizations:
- Improved data quality through cleaning transformations.
- Enhanced decision-making capabilities based on data-driven insights.
- Cost savings by leveraging scalable and efficient Azure services.
- Better understanding of healthcare operations and patient trends.
