# Distributed Recommendation Engine

A distributed content-based recommendation system built using Hadoop HDFS, Apache Spark, and Apache HBase.

The project demonstrates scalable data storage, processing, and recommendation generation using big data technologies on the Amazon Product Sales dataset.

---

## Features

- Distributed data storage using Hadoop HDFS
- Data cleaning and transformation with Apache Spark
- Data persistence and retrieval via Apache HBase
- Analytical insights using Spark (pricing, ratings, category analysis)
- Content-based recommendation system using cosine similarity
- Feature engineering with:
  - StringIndexer
  - OneHotEncoder
  - VectorAssembler
- Spark ML pipeline for scalable preprocessing
- Recommendation storage in HBase for fast lookup

---

## Requirements

- Hadoop (HDFS)
- Apache Spark
- Apache HBase
- Python 3.9+
- HappyBase
- pandas
- matplotlib
- seaborn
