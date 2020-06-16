Flink S3 Connector
=========================================

## Working
This Job is to read the data from S3 bucket and print it to the console. Data is in the Parquet Avro format.

## Change Credentials of AWS S3.
1. Add the access key and secret key in the resources/core-site.xml
2. Change the required fields of AwsS3Configurations object inside ETL.scala.

## Run The Project

### Hit command inside the project directory
```
sbt clean compile
sbt run
```