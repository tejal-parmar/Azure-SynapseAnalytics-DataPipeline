# azure-data-engineering-project
Real time end-to-end Azure Data Engineering project to build a data pipeline using Azure Synapse Analytics, Azure Storage and Azure Synapse SQL pool to perform data analysis on the 2021 Olympics dataset.

  - Extract data from the API using <b>ADF</b> (Azure Data Factory - data pipeline tool available on Azure)
  - Load data onto <b>Azure Data Lake Gen 2 storage</b>
  - Using <b>Azure Databricks</b>, to write spark code, transform the data and load the data back to Azure Data Lake Gen 2 storage
  - Using <b>Synapse Analytics</b>, to run SQL queries on top of the transformed data, to get the insights and visualization

#AzureCloud #Databricks #DataFactory #Spark #SynapseAnalytics #DataLake

## Azure Services
  - <b>Data Factory</b> : Data integration service that enables you to create, schedule, and manage data pipelines for efficient data movement and transformation between various sources and destinations in Azure and beyond. It simplifies ETL (Extract, Transform, Load) and data integration tasks.
  - <b>Data Lake Gen 2</b> : Data lake solution that combines the capabilities of a data lake with the power of Azure Blob Storage, allowing you to store and analyze large volumes of structured and unstructured data with enhanced performance, security, and analytics capabilities, can perform SQL queries.
  - <b>Azure Databricks</b> : Databricks is a unified analytics platform built on top of Apache Spark, designed to help data engineers and data scientists collaborate on big data processing and machine learning tasks. It provides tools for data exploration, data processing, and building machine learning models in a collaborative and scalable environment.
  - <b>Synapse Analytics</b> : SQL Data Warehouse, is a cloud-based analytics service provided by Microsoft Azure. It combines big data and data warehousing into a single integrated platform, allowing organizations to analyze and process large volumes of data for business intelligence and data analytics purposes.

Original Dataset : [Source](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

## Project Steps
  - Understanding the 2021 Olympics dataset
  - Creating Azure Resource Group
  - Creating Azure Storage account
  - Creating a container in Azure Storage
  - Uploading data files in Azure Storage Container
  - Creating a Azure Synapse workspace
  - Creating a SQL pool in Azure Synapse workspace
  - Creating tables in SQL pool
  - Create a pipeline to ingest data from Azure storage into SQL pool tables
  - Load data from Azure Synapse into Power BI
  - Creating visualizations in Power BI
  - Publishing Power BI dashboard in Azure Synapse workspace

