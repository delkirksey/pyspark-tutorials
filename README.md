# PySpark Tutorials

This repository holds several applications that were completed as part of Pluralsight's Beginning Data Exploration and Analysis with Apache Spark

The course is all about data preparation i.e. cleaning, trasnforming, and summarizing data using Spark.

---

### Module 1: Getting Started with Spark's Resilient Distributed Datasets

**Overview:**

- Understanding the role of Spark in data analysis
- Understand RDDs and their characteristics
- Install Spark in a local environment
- Load data from a file
- Read data from an RDD

**What did I learn:** 

- The role of Spark in data analysis
- Loading data from a file is a Spark **transformation**
- Reading data from a file is a Spark **action**
- RDDs are partitioned, read-only collections which know their lineage
- Spark transformations are lazily evaluated

**Tutorial:** [Load a Data Set](https://github.com/delkirksey/pyspark-tutorials/tree/master/apps/tutorial_1)

---

### Module 2: Transforming & Cleaning Unstructured Data

**Overview:**

- Transform data using functional constructs
- Clean unstructured data
- Identify and remove anomalies and missing values

**What did I learn:**

- How to *filter* records matching certain conditions
- How to *transform* data using the map operation
- How to compute aggregates using the *reduce* operation
- How to identify and remove anomalies and missing values

**Tutorial:** [Analyzing Crime in New York City](https://github.com/delkirksey/pyspark-tutorials/tree/master/apps/tutorial_2_nycrime)

---

### Module 3: Summarizing Data Along Dimensions

**Overview:**

- Learn to represent records as **Pair RDDs**
- Summarize Pair RDDs using *reduceByKey* and *combineByKey*
- Merge data from separate RDDs

**What did I learn:**

- How to represent records as Pair RDDs
- How to summarize Pair RDDs using *reduceByKey* and *combineByKey*
- How to merge data from separate RDDs

**Tutorial:** [Analyzing LA Dodgers Traffic](https://github.com/delkirksey/pyspark-tutorials/tree/master/apps/tutorial_3_dodgers)

---

### Module 4: Modeling Relationships in the Marvel Social Universe

**Overview:**

- Find the most influential characters
- Build a Co-occurence network from the given data
- Find the most important cliques

**What did I learn:**

-