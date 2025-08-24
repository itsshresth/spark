# IPL Data Analytics with Apache Spark & Databricks

## Project Overview

This project analyzes the IPL 2017 ball-by-ball dataset using Apache Spark on Databricks with data stored on AWS S3. It demonstrates a scalable ETL pipeline for ingestion, transformation, and analysis, followed by visualizations for actionable insights.

## Tech Stack

Python, Spark SQL

Apache Spark (DataFrames, SQL), Databricks

AWS S3

Matplotlib, Seaborn


## Workflow

1. Data Ingestion – Loaded datasets (ball-by-ball, matches, players) from AWS S3 into Databricks with defined schemas.


2. Data Transformation – Cleaned missing values, performed filtering, grouping, and aggregations using Spark DataFrames.


3. Analysis with Spark SQL – Extracted insights on top scorers, toss impact on outcomes, and team/player performance.


4. Visualization – Created plots for economical bowlers, dismissal patterns, and winning trends.



## Key Insights

Identified top scorers and best bowlers of IPL 2017.

Analyzed how toss decisions influenced match results.

Visualized player and team-level performance trends.


## How to Run

1. Clone the repository.


2. Upload datasets to AWS S3 or local storage.


3. Import notebooks/scripts into Databricks and update paths.


4. Execute transformations, queries, and visualizations.



## Learnings

Building ETL pipelines using Spark on Databricks.

Writing efficient Spark SQL queries for large datasets.

Applying data visualization to highlight analytical findings.
