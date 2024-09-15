# Learning PySpark

## [Link to Video](https://youtu.be/_C8kWso4ne4?si=LYAhUdw8oa24vraE)

## Jupyter Notebook

View the [Jupyter Notebook](./PySpark%20Demo.ipynb) for the detailed code on implementing PySpark.

## Insurance Notebooks

| #   | Notebook                                                                                              | Description                                                                    |
| --- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 1.  | [Insurance Price Prediction](./Insurance%20Notebooks/1_Health%20Insurance%20Price%20Prediction.ipynb) | Predicting the price of health insurance using Linear Regression               |
| 2.  | [Insurance Risk Score Prediction](./Insurance%20Notebooks/2_Insurance%20Risk%20Score.ipynb)           | Predicting the risk score (Low, Medium, High) of insurance using Random Forest |
| 3.  | [Insurance Fraud Detection](./Insurance%20Notebooks/3_Insurance%20Fraud%20Detection.ipynb)            | Detecting fraud in insurance using Random Forest                               |

## Usage

1. After cloning the repository, run the following command to create a virtual environment:

   ```bash
   python -m venv .venv
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

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
