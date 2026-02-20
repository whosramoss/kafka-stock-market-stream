# Kafka Stock Market Stream

Real-time stock market data streaming with Apache Kafka: Python producer and consumer notebooks that publish and consume JSON messages from a Kafka topic, with optional persistence to AWS S3 for querying via Glue and Athena. Setup targets Ubuntu.

---

## About

This project demonstrates a **streaming pipeline** that ingests stock market data in real time using Apache Kafka, with optional downstream storage and querying on AWS (S3, Glue, Athena). It covers producer/consumer patterns, topic configuration, and integration with a cloud data lake. All configuration (broker, topic name, paths, and AWS settings) is centralized in variables at the top of each notebook.
