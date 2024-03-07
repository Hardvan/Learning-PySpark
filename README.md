# Learning PySpark

## [Link to Video](https://youtu.be/_C8kWso4ne4?si=LYAhUdw8oa24vraE)

## What is Apache Spark?

- Fast and general-purpose cluster computing system
- Speed: Run programs up to 100x faster than Hadoop MapReduce in memory, or 10x faster on disk
- General-purpose: Combine SQL, streaming, and complex analytics
- Powerful caching
- Real-time stream processing
- It provides high-level APIs in Java, Scala, Python and R

## Spark Ecosystem

- **Engine**:
  - Spark Core: The base engine for large-scale parallel and distributed data processing
- **Management**:
  - Yarn: Resource management
  - Mesos: Cluster management
- **Libraries**:
  - Spark SQL: SQL and structured data processing
  - MLlib: Machine learning
  - GraphX: Graph processing
  - Spark Streaming: Real-time data processing
- **Programming**:
  - Scala, Java, Python, R
- **Storage**:
  - HDFS, Local FS (file system), RDBMS, NoSQL, Amazon S3 etc.

## RDD (Resilient Distributed Dataset)

- Fault-tolerant collection of elements that can be operated on in parallel
- Immutable distributed collection of objects
