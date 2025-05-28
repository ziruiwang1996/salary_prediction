## Project Rework In Progress:
check my repo at: https://github.com/ziruiwang1996/data-engineering-pipeline

New project focues on buiding a scalable ELT pipeleine that:
- has a data warehouse after primary data cleaning and normalization
- uses Airflow to orchestrate file drop (Minio), extract (pyspark) - load (postgreSQL) - transform (dbt)
- integrates with Tableau for data visualization
- integrates with Tensorflow/sci-kit learn/pytorch for model trainning 
