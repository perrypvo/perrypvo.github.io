## Introduction

This repository contains mainly notes from learning Apache Spark by [Perry Vo](https://github.com/perrypvo).


## Cheat Sheets

+ [Python Basics](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PythonForDataScience.pdf)
+ [Pandas Basics](http://datacamp-community.s3.amazonaws.com/3857975e-e12f-406a-b3e8-7d627217e952)
+ [Numpy Basics](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Numpy_Python_Cheat_Sheet.pdf)
+ [Scikit-Learn](http://datacamp-community.s3.amazonaws.com/5433fa18-9f43-44cc-b228-74672efcd116)
+ [RDD Basics](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PySpark_Cheat_Sheet_Python.pdf)
+ [DataFrame Basics](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PySpark_SQL_Cheat_Sheet_Python.pdf)
+ [Apache Spark Cheat Sheet](https://hackr.io/tutorials/learn-apache-spark)

Microsoft Learning paths for Data Engineering:
https://github.com/solliancenet/microsoft-learning-paths-databricks-notebooks/tree/master/data-engineering/DBC


## Notes
Google Dataproc vs Dataflow:
- Google dataproc:  provides hadoop cluster on GCP and tools such as Apache Pig, Hive, and Spark. 
- Google dataflow:  based on Apache Beam

Here are three main points to consider while trying to choose between Dataproc and Dataflow

Provisioning
Dataproc - Manual provisioning of clusters
Dataflow - Serverless. Automatic provisioning of clusters

Hadoop Dependencies
Dataproc should be used if the processing has any dependencies to tools in the Hadoop ecosystem.

Portability
Dataflow/Beam provides a clear separation between processing logic and the underlying execution engine. This helps with portability across different execution engines that support the Beam runtime, i.e. the same pipeline code can run seamlessly on either Dataflow, Spark or Flink.

# Dataflow Templates
http://github.com/GoogleCloudPlatform/DataflowTemplates

