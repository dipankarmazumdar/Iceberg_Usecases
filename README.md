# Apache Iceberg Use Cases:

This repository contains a collection of Jupyter notebooks and Python code demonstrating various operations and patterns with Apache Iceberg and Apache Spark. The examples cover a range of operations from DDL and DML operations, Change Data Capture (CDC), Machine Learning (ML) inference pipelines, implementing Slowly Changing Dimensions Type 2 (SCD2), to ensuring data quality through write audit publish patterns. Additionally, there's a practical example of producing data to Amazon Kinesis from the OpenWeatherData API.

## Contents

- **`Spark_iceberg.ipynb**`: Demonstrates how to perform various Data Definition Language (DDL), Data Manipulation Language (DML), and read operations on Apache Iceberg tables using Apache Spark.

- **CDC_iceberg.ipynb**: Showcases how to implement Change Data Capture (CDC) from Iceberg tables to downstream applications. 

- **ML_inference.ipynb**: Explains how to build Machine Learning inference pipelines using Apache Iceberg and Spark. 

- **SCD2_iceberg.ipynb**: Provides a method to implement Slowly Changing Dimensions Type 2 (SCD2) with Apache Iceberg and Spark. 

- **WriteAuditPublish.ipynb**: Illustrates how to implement data quality using the write audit publish pattern in Apache Iceberg.

- **ProducerKinesis.py**: A Python script that acts as a producer, reading streaming data from the OpenWeatherData API and storing it in an Amazon Kinesis data stream. 

## Getting Started

To get started with these examples, clone this repository to your local machine or Jupyter notebook environment, and ensure you have Apache Spark and Apache Iceberg set up. For the `ProducerKinesis.py`, you'll need an AWS account and an Amazon Kinesis stream configured.

## Prerequisites:
- Apache Spark
- Apache Iceberg
- AWS account (for the ProducerKinesis.py example)
- Jupyter Notebook or Lab environment
