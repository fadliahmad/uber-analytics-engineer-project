# uber-analytics-engineer-project

## Introduction 
The goal of this project is to perform end-to-end data engineer analytics on Uber dataset using various tools and technologies, including Google Cloud Storage, Python, Google Compute Engine, Mage Data Pipeline Tool, BigQuery, and Looker Studio. 

Executive summary: 

🔧 What I do:
    📥 Importing and load the dataset into Google Cloud Storage
    🐍 Creating a python notebook for data extraction and transformation
    🖥️ Creating a virtual machine instance to run Mage.ai pipeline tools
    🧙‍♂️ Creating data pipeline using Mage.ai 
    🏭 Managing data warehouse in BigQuery (dimensional, fact, and mart table concept) 
    📊 Creating a dashboard and analyzing the data 
      
📒 Notes: the dimentional data table is not really necessary, but it's just for the understanding the concept of dim-fact-mart table. 

## Architecture 
🏛️ The architecture I used in this project: 
<img src="img/architecture.jpg">

## Tools 
🔧 Tools I used in this project:
    🖥️ Google Cloud Platform
        - Google Cloud Storage 
        - Google Compute Engine 
        - Google BigQuery 
        - Google Looker Data Studio 
    🐍 Python 
    🧙‍♂️ Mage.ai 
    🗃️ SQL

## Dataset 
TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset used in this project - https://github.com/fadliahmad/uber-analytics-engineer-project/tree/master/data
More info about dataset can be found here:

1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model 
📑 Data modeling in this project: 
<img src="img/Uber Data Modelling.jpeg">

## Creating Google Cloud Storage Bucket 
📥 Its an online file storage which is provided as a service by GCP. It helps us store, retrieve files from anywhere in the cloud with an internet connection.
<img src="img/Google Cloud Storage - Bucket.png>

## Creating Virtual Machine Instance to Run Mage.ai 
🖥️ Its the part of the GCP suite that helps us run virtual machines to run our applications. 
<img src="img/Vm Instance.png> 

## Creating Virtual Machine Instance to Run Mage.ai 
🧙‍♂️ Mage is the latest open source tool to set up your ETL pipeline. This tools helps you with focussing only your business logic using certain existing templates it provides to — ‘load’,’transform’ and ‘extract’ the data. 
<img src="img/mage pipeline.png> 

## Managing data warehouse in BigQuery 
🏭 Its a warehouse provided by Google which helps us store, analyse large scale data sets using a SQL type interface and query language. 
<img src="img/BigQuery.png> 

## Dashboard 
🔍 Dashboard result: 
<img src="img/Uber_Data_Engineer_Analytics_Project_Dashboard.jpg"> 
