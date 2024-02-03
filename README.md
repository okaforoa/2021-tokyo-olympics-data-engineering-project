# 2021 Tokyo Olympics Azure Data Engineering Project

## Project Overview
This project was developed to construct a comprehensive data engineering pipeline focused on the 2021 Tokyo Olympics, aiming to provide deep insights and analytics from the event data. Utilizing Azure services for orchestration, storage, and analytics, alongside Databricks for data transformation, the solution handles data from ingestion to analysis, ensuring high data quality and accessibility for complex queries and reporting.

## Solution Architecture
![Data Engineer Project](https://github.com/okaforoa/2021-tokyo-olympics-data-engineering-project/blob/main/images/2021%20Tokyo%20Olympics%20Data%20Engineer%20Project.jpg)

The architecture is structured as follows, depicted in the provided diagram:
- **Data Source**: GitHub hosts the originating Olympic data sets.
- **Data Ingestion**: Data Factory orchestrates the ingestion of data from GitHub to the raw data storage.
- **Raw Data Store**: Azure Blob Storage serves as the repository for raw data.
- **Data Transformation**: Databricks processes the raw data, performing cleansing, aggregation, and preparation for analysis.
- **Transformed Data Store**: The processed data is stored back into Azure Blob Storage, optimized for analytics.
- **Analytics**: Azure Synapse Analytics is used to perform complex analytics and produce insights from the transformed data.

## Objectives
- To establish a resilient and scalable data pipeline capable of handling diverse Olympic data.
- To transform raw Olympic data into an analyzable format, enabling complex analytical queries.
- To uncover insights that can drive data-driven decisions for stakeholders interested in Olympic events.

## Technologies Used
- **GitHub**: For version control and data source management.
- **Azure Data Factory**: For orchestrating and automating the data ingestion process.
- **Azure Blob Storage**: For storing raw and processed data.
- **Databricks**: For robust data transformation capabilities.
- **Azure Synapse Analytics**: For comprehensive analytics and business intelligence operations.

## Acknowledgments
- I would like to thank Darshil Parmar for inspiring me to complete this project. 
