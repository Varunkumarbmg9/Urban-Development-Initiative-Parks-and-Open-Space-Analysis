# Urban-Development-Initiative-Parks-and-Open-Space-Analysis

# Overview
This project, under the Urban Development Initiative, evaluates park accessibility and utilization in urban areas to identify gaps and provide actionable insights. Using data cleaning, processing, and advanced analytical tools, we analyzed park datasets for three major U.S. cities: Chicago, Norwalk, and New York.

# Objectives
- Assess park accessibility and distribution across urban areas.
- Provide data-driven recommendations to improve park utilization and accessibility.
- Compare tool performance (Hive vs. Spark) for large-scale data analysis.

# Project Components
- Cloud Environment Setup:

  - Used Google Cloud Platform (GCP) for scalable storage and computing.
  - Uploaded cleaned datasets into GCP buckets for further analysis.
- Data Cleaning and Processing:

  - Cleaned datasets using OpenRefine, ensuring consistency and completeness.
  - Removed duplicates, standardized data formats, and addressed missing values.
- Insights and Analysis:

  - Analyzed datasets using BigQuery, Hive, and Spark.
  - Compared Hive and Spark performance to optimize runtime efficiency.

# Technologies Used
- Cloud Platform: Google Cloud Platform (GCP)
- Data Processing: Hadoop (Hive, Spark), BigQuery
- Data Cleaning: OpenRefine
- Programming Languages: SQL, Python
- Tools: Dataproc, Cloud Storage

# Performance Insights

- Chicago Dataset:

  - Query: Count of reachable parks by ZIP area.
  - Hive Run Time: 6.615 seconds
  - Spark Run Time: 13.349 seconds
  - (Hive was faster, taking approximately half the time.)

- Norwalk Dataset:

  - Query: Parks ownership under one entity.
  - Hive Run Time: 15.401 seconds
  - Spark Run Time: 1.045 seconds
  - (Spark significantly outperformed Hive, running ~15x faster.)

- New York Dataset:

  - Query: Top 10 largest parks.
  - Hive Run Time: 6.329 seconds
  - Spark Run Time: 7.851 seconds
  - (Hive was slightly faster than Spark.)
These results highlight the strengths of each tool depending on query complexity and dataset size.

# Key Findings
- Chicago: Analyzed park distribution and accessibility by ward and ZIP code.
- Norwalk: Examined park categories and ownership patterns.
- New York: Evaluated total park area and identified the largest parks.

