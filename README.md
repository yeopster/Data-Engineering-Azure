# Data Engineering with Microsoft Azure Service

## Introduction
In this project I have learned to use and understand the basic of Microsoft Azure Cloud Services. I am able to do basic data engineering using Microsoft Azure Services by using Storage Account, Data Factory (V2), Azure Databricks, Synapse workspace and Microsoft Power BI.

## Data Architecture
![Data Pipeline](Datapipelineazure.png)

Data architecture basis from this project is raw data are ingest into Data Factory using copy data function that use HTTP-linked service to copy data from Github raw file to Azure Data Factory.

Data from Azure Data Factory is sink to Data Lake Storage Container after validation is done.
