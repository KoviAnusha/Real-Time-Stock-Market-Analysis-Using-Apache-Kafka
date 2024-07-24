# Stock Market Real Time Analysis Using Apache Kafka

![Data Architecture](./Data%20Architecture.png)

Steps:

1. Create a EC2 instance of Amazon Linux AMI.
2. Download and install Apache Kafka, Apache Zookeeper, and Java.
3. Run Apache Zookeeper on one terminal.
4. Write a python script for Apache Kafka Producer. In this script, simulate the dataset such that it takes sample rows for every 1 second and dumps to consumer.
5. Write a python script for Apache Kafka Consumer. In this script, whatever the data that comes from producer, the consumer needs to collect and store it in S3. 
6. Build crawlers using AWS Glue
7. The data can be seen on Athena
8. Writing a AWS Glue Job using Python Shell Script
   - Connect to Redshift
   - Load data from CSV files in S3 to Redshift

