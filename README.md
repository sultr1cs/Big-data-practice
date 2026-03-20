Machine Learning and PySpark Practice
This repository contains a series of practical implementations focused on Big Data processing, distributed computing, and predictive modeling using the Apache Spark ecosystem.

Project Overview
The project demonstrates the application of PySpark for handling large-scale datasets, transitioning from low-level RDD operations to high-level Machine Learning pipelines. The work is divided into data engineering tasks and supervised learning applications.

Summary of Completed Work
Data Engineering & Core Spark

RDD Operations: Implementation of fundamental transformations (map, filter, flatMap) and actions (collect, count, reduce) to manipulate unstructured data.

Spark SQL & DataFrames: Structured data analysis using Spark SQL for relational queries and DataFrame API for complex data aggregations and joins.

ETL Pipelines: Processing various data formats (CSV, text) including HollywoodMovies.csv and ITI_data.csv to prepare them for analytical tasks.

Machine Learning (MLlib)

Logistic Regression: Development of a classification model to analyze binary outcomes, specifically focused on categorical data processing and vectorization.

Customer Churn Analysis: A dedicated end-to-end ML workflow using customer_churn.csv to identify patterns in user retention. This includes feature scaling, string indexing, and model evaluation.

Predictive Modeling: Generation of predictions for new data subsets (new_customers.csv), resulting in exported results such as customer_churn_predictions.csv and identifying high_risk_customers.csv.

Algorithm Exploration: Comparative analysis of different ML algorithms within the PySpark ML library to determine the most effective approach for classification and regression tasks.

Technical Competencies
Distributed Computing: Managing data partitions and memory persistence in Spark.

Feature Engineering: Utilizing VectorAssembler and StringIndexer for pipeline construction.

Model Assessment: Evaluating performance metrics for Big Data models.
