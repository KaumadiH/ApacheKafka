# ApacheKafka - Simulated Weather in Sri Lanka 

## Introduction
In this project, Real-Time Weather data in Sri Lanka were simulated to understand how Apache Kafka Streams operates. AWS free t3.micro machine and designed the data stream was used to prevent any memory problems in AWS instance. Some sample JSON files from the available datasets were used to simulate the stream of each event. S3 bucket is used to load all streaming data and by using a Crawler, data are crawled to design a table structure for the AWS Glue Data Catalog which allowed querying in Amazon Athena.

## Technologies used 
*   Python
*   Apache Kafka
*   Amazon Web Services
1.   EC2
2.   S3
3.   Crawler
4.   Amazon Athena


## Output
As long as the servers and scripts were operating, fresh data was being uploaded to the S3 bucket and made available for querying in Amazon Athena.
