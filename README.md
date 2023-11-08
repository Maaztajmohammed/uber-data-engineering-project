# Uber Data Engineering Project

### Introduction 
The project aims to build a data model using a dataset and create a data pipeline to transform the dataset according to the data model and store the data into the Data Warehouse (Google BigQuery)

### Data Model 
![Uber Data Model](https://github.com/Maaztajmohammed/uber-data-engineering-project/blob/main/Uber%20Data%20Model.jpeg)

### Cloud Platform Used :
Google Cloud Platform (GCP)

### Cloud Services Used : 
1. Compute Engine - Used this service to create an instance to deploy the orchestration tool and run the pipeline.
2. Cloud Storage - Used to store the raw data file (uber_data.csv)
3. BigQuery - Used this datawarehouse service to store the data divided in different tables in one database.

### Orcestration Tool :
Mage-AI

### Project Flow : 
Load_data_from_CloudStorge ==> Transform_data_according_to_the_data_model_using_Mage-AI ==> Load_the_data_into_BigQuery


