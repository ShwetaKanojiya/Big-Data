## 🏗️ What is Big Data?

**Big Data** refers to extremely large and complex datasets that cannot be processed efficiently using traditional data processing systems.  
It involves collecting, storing, and analyzing massive amounts of structured, semi-structured, and unstructured data to derive valuable insights and support decision-making.

---
<img src="https://github.com/ShwetaKanojiya/Big-Data/blob/main/hadoop.webp" width="800"/>

## ⚙️ The V’s of Big Data

Big Data is often defined by several key characteristics, known as the **V’s**:

- **Volume:** The vast amount of data generated every second.
- **Velocity:** The speed at which new data is generated and processed.
- **Variety:** Different types of data (text, images, audio, video, logs, etc.).
- **Veracity:** The quality, accuracy, and trustworthiness of data.
- **Value:** The potential insights and benefits that can be derived from data.

---

## 🔄 ETL and ELT

- **ETL (Extract, Transform, Load):**  
  Data is first extracted from various sources, transformed into a usable format, and then loaded into a target data warehouse.

- **ELT (Extract, Load, Transform):**  
  Data is extracted and loaded into the target system first, and transformation happens within the data warehouse itself — often used in cloud-based data systems.

---

## 🧮 Data Processing

**Data Processing** refers to converting raw data into meaningful information through operations such as:
- Data Cleaning
- Transformation
- Aggregation
- Analysis
- Visualization

It can be categorized as:
- **Batch Processing:** Processes large volumes of data at once (e.g., Hadoop MapReduce).
- **Stream Processing:** Processes real-time, continuous data streams (e.g., Apache Kafka, Apache Spark Streaming).

---

## 🐘 Hadoop and Its Components

**Hadoop** is an open-source framework that allows for distributed processing of large datasets across clusters of computers using simple programming models.

### Core Components:
1. **HDFS (Hadoop Distributed File System):**  
   Responsible for reliable and scalable storage across multiple nodes.
2. **MapReduce:**  
   A programming model for parallel data processing.
3. **YARN (Yet Another Resource Negotiator):**  
   Manages and schedules cluster resources for multiple applications.
4. **Common Utilities:**  
   Provides essential Java libraries and OS-level abstractions.

---

## 🧩 MapReduce and Its Components

**MapReduce** is a programming model used for processing and generating large datasets with a parallel, distributed algorithm on a cluster.

### Components:
1. **Map Phase:**  
   Processes input data and produces intermediate key-value pairs.
2. **Shuffle and Sort:**  
   Sorts and groups data by key before sending it to the reducer.
3. **Reduce Phase:**  
   Merges all intermediate values associated with the same key and outputs the final result.

---

## 🧠 YARN and Its Components

**YARN (Yet Another Resource Negotiator)** is the cluster resource management layer of Hadoop that enables multiple data processing engines to run simultaneously.

### Components:
1. **ResourceManager:** Allocates resources among applications.
2. **NodeManager:** Monitors and manages resources on individual nodes.
3. **ApplicationMaster:** Manages the execution of a single application.
4. **Container:** A unit of resources (CPU, memory) where tasks execute.

---

## ⚡ Apache Spark and Its Components

**Apache Spark** is a fast, open-source processing engine designed for large-scale data analytics.  
It provides high-level APIs in Java, Scala, Python, and R and supports in-memory processing for speed and efficiency.

### Components:
1. **Spark Core:** Fundamental engine for distributed data processing.
2. **Spark SQL:** For structured data and SQL queries.
3. **Spark Streaming:** For real-time data stream processing.
4. **MLlib:** A machine learning library.
5. **GraphX:** For graph computation and analytics.

---

## 🐝 Apache Hive and Its Components

**Apache Hive** is a data warehouse infrastructure built on top of Hadoop that provides an SQL-like interface to query and analyze large datasets stored in HDFS.

### Components:
1. **Metastore:** Stores metadata about tables and partitions.
2. **Driver:** Manages the lifecycle of a HiveQL statement.
3. **Compiler:** Parses and compiles HiveQL into execution plans.
4. **Execution Engine:** Executes query plans on Hadoop.
5. **HiveQL:** SQL-like query language for Hadoop.

---

## 📡 Apache Kafka and Its Components

**Apache Kafka** is a distributed event streaming platform used for building real-time data pipelines and streaming applications.  
It is known for its high throughput, scalability, and fault tolerance.

### Components:
1. **Producer:** Publishes data (messages) to Kafka topics.
2. **Consumer:** Subscribes and reads data from topics.
3. **Broker:** Manages data storage and message delivery.
4. **Topic:** A logical channel to which records are published.
5. **ZooKeeper (Legacy):** Manages cluster coordination (now replaced by Kafka Raft in newer versions).

---

## 🚀 Summary

| Technology | Purpose | Key Features |
|-------------|----------|---------------|
| **Hadoop** | Distributed storage & processing | HDFS, MapReduce, YARN |
| **MapReduce** | Batch data processing | Map + Reduce model |
| **YARN** | Cluster resource management | ResourceManager, NodeManager |
| **Spark** | In-memory data processing | Fast, Scalable, Multi-language support |
| **Hive** | Data warehousing & SQL querying | HiveQL, Metastore |
| **Kafka** | Real-time data streaming | Producers, Consumers, Brokers |


---
