# azure-data-engineering-project
Real time end-to-end Azure Data Engineering project to analyze Olympic data using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

  - Extract data from the API using Azure Data Factory (data pipeline tool available on Azure)
  - Load data onto Azure Data Lake Gen 2 storage
  - Using Azure Databricks, to write spark code, transform the data and load the data back to Azure Data Lake Gen 2 storage
  - Using Synapse Analytics, to run SQL queries on top of the transformed data, to get the insights and visualization

#AzureCloud #Databricks #DataFactory #Spark #SynapseAnalytics #DataLake

## Azure Services
  - <b>Data Factory</b> : Data integration service that enables you to create, schedule, and manage data pipelines for efficient data movement and transformation between various sources and destinations in Azure and beyond. It simplifies ETL (Extract, Transform, Load) and data integration tasks.
  - <b>Data Lake Gen 2</b> : Data lake solution that combines the capabilities of a data lake with the power of Azure Blob Storage, allowing you to store and analyze large volumes of structured and unstructured data with enhanced performance, security, and analytics capabilities, can perform SQL queries.
  - <b>Azure Databricks</b> : Databricks is a unified analytics platform built on top of Apache Spark, designed to help data engineers and data scientists collaborate on big data processing and machine learning tasks. It provides tools for data exploration, data processing, and building machine learning models in a collaborative and scalable environment.
  - <b>Synapse Analytics</b> : SQL Data Warehouse, is a cloud-based analytics service provided by Microsoft Azure. It combines big data and data warehousing into a single integrated platform, allowing organizations to analyze and process large volumes of data for business intelligence and data analytics purposes.



Requirements :  
  - we have azure blob storage account where we are getting all raw data (employee, department) in json format.
  - we need to create pipeline and schedule it on daily basis which will pick data from raw container to specific employee and department container and we need to dump file in csv format.
  - we need to create pipeline which will be able to join the employee and department file based on department id and need to store inro emp_dept container.
  - we should be able to save aggregated information of total department wise employee salary and grouping of job id.
