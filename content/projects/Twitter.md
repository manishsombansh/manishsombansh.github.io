---
date: '2019-03-01'
title: 'Scalable High-Performance Twitter Analytics Web Service'
github: ''
external: 'https://medium.com/@manishsombansh/scalable-high-performance-twitter-analytics-web-service-28a3b524dcaf'
company : 'CMU'
tech:
- Java
- Undertow
- Apache Spark
- Scala
- Maven
- MySQL
- Apache HBase
- Terraform
- Google Cloud Platform (GCP)
- AWS CloudWatch
showInProjects: false
---

Implemented a high performance, fault-tolerant web service on AWS EC2 clusters for 1TB Twitter data analysis with read queries and achieved over 25,000 RPS on a limited budget given to work upon. Processed 1TB raw data using Apache Spark and Scala to perform ETL and load data into MySQL and HBase database systems. Used Undertow framework and load balancer for front end. Employed backend using MySQL and HBase, improved performance by implementing several optimizations ranging from schema design, database parameter tuning, horizontal scaling, replication and sharding, and monitored performance using AWS CloudWatch to identify performance bottlenecks. Migrated the web service to use managed web services provided by Amazon in the final phase of the project. Used AWS LightSail for the front end and RDS, Aurora for the backend.
