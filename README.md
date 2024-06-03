# Azure Data Pipeline Project

In this project, we are going to build a data pipeline using Azure services. The pipeline performs data ingestion, storage, transformation, analysis, and visualization.

## Table of Contents
1. Introduction
2. Dataset Description
3. Architecture Overview
4. Data Pipeline Creation
5. Transformation and Analytics
6. Visualization and Power BI
7. Conclusion

## Introduction
This project implements a data pipeline using Azure Data Factory, Azure Data Lake Storage Gen2, PySpark, Synapse Analytics, and Power BI.

## Dataset Description
We used a synthetic healthcare dataset with 10,000 records. It includes patient demographics, medical conditions, admission details, and more.

## Architecture Overview
![Architectural Diagram]([paste-your-copied-image-url-here](https://github.com/harshrai868/Azure-Project/blob/main/AD.jpg))

![Architectural Design] ()


The architecture involves:
- **Azure Data Factory (ADF):** Orchestrates data movement and transformations.
- **Azure Data Lake Storage Gen2 (ADLS):** Stores raw and transformed data.
- **Synapse Analytics:** Analyzes cleaned data.
- **Power BI:** Creates interactive dashboards for visualization.

## Data Pipeline Creation
### Data Ingestion
- Used ADF Copy Activity to ingest data from CSV files into ADLS Gen2.

### Data Storage
- Stored ingested data in ADLS Gen2 for scalability and flexibility.

### Data Transformation
- Used PySpark within ADF for data cleaning and transformation tasks.

## Transformation and Analytics
### Data Cleaning with PySpark
Handled missing values, corrected inconsistencies, and performed feature engineering.

### Analysis with Synapse Analytics
Transferred cleaned data from ADLS to Synapse and performed SQL queries for analysis.

## Visualization and Power BI
Created visuals in Power BI, including bar charts, pie charts, and line charts. Published and shared the dashboard via Power BI service.

## Conclusion
Implementing this data pipeline improved data quality, facilitated data-driven insights, and enhanced operational efficiency.


