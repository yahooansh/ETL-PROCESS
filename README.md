# ETL-PROCESS
Organizations often gain data from multiple sources, filter and clean it and then load the data onto different systems for visualizations and analysis. Over time, many of these systems may become disconnected and not performing optimally.
As a Big Data Developer, trying to combine data from multiple sources into one or more other sinks. The go-to technologies for transferring data are often Apache Kafka and Spark Streaming. In this Project i will mimic an ETL process (short for extract, transform and load) using Spark Streaming and different data sources.


For this project, spark streaming will be reading data. The data will then be aggregated and sent to a Kafka sink depending on the type of data that it is.
For any data that involves sitting or standing, the data is sent to a Kafka topic called
"idle". For any data other than sitting or standing, the data is sent to a Kafka topic called "active".
Two consumers should then read the data and display the activity and time according to the type of activity. 
###### Google cloud platform was used for it. 

## Downloading zookeeper
<img width="655" alt="1" src="https://github.com/user-attachments/assets/d6f5cb51-db40-42ce-bc7a-9adcf57811fe">

## Running kafka 
<img width="629" alt="2" src="https://github.com/user-attachments/assets/47ecb29b-d77a-40c6-9d1c-4c3d27d73c7d">

## Creating two topics idle and active
<img width="957" alt="3" src="https://github.com/user-attachments/assets/eb0bbc8a-fdd0-421b-8449-a48d97e63dd9">

## Creating Scala streaming
<img width="682" alt="4" src="https://github.com/user-attachments/assets/ad66194c-888e-4c6e-b16b-ff5ca93605e0">
<img width="670" alt="5" src="https://github.com/user-attachments/assets/ec4e742f-d38d-4f31-a117-7da5e08834a0">

## Creating Checkpoint directory and uploading data/ json files in local system
<img width="656" alt="6" src="https://github.com/user-attachments/assets/fcac77bf-8a53-4cc6-a3c2-0fe675520ae3">

## Uploading files from local system to Hadoop and consumers reading the data
<img width="955" alt="7" src="https://github.com/user-attachments/assets/3c1755ed-33e3-41ce-a37c-21a4bb1a6a68">
<img width="958" alt="8" src="https://github.com/user-attachments/assets/843934a2-2ccc-457b-96d5-28608e18dff5">

## Flume setup
<img width="761" alt="9" src="https://github.com/user-attachments/assets/ae975ac7-ef03-45c1-a446-044a75b17f51">

## Creating directory ,changing directory, changing file owner 
<img width="805" alt="10" src="https://github.com/user-attachments/assets/cfb87a40-45a7-41d3-aaa1-687592c3e491">

## Cross checking
<img width="428" alt="11" src="https://github.com/user-attachments/assets/e6a41349-5adc-42a3-ad9b-e71dea7207fc">
<img width="559" alt="12" src="https://github.com/user-attachments/assets/e8e85646-19f1-4c37-9ff9-1318f16ec4b6">

## Starting flume agent
<img width="947" alt="13" src="https://github.com/user-attachments/assets/734924cc-be62-4332-b1a6-6b01774fed43">

## Cross checking
<img width="710" alt="14" src="https://github.com/user-attachments/assets/1423bc2b-48f1-44aa-b07a-bed5097326b0">
