# RedditDataEngineering
Data pipeline with Reddit, Airflow, Celery, Postgres, S3, AWS Glue, Athena, and Redshift

## Architecture
![image](https://github.com/user-attachments/assets/128c2d27-ed4e-449b-9208-b6180ee48ed7)

## Pipeline
1. Extract data from Reddit API
2. store the raw data in S3 bucket from Airflow
3. Transform the data using AWS Glue and Athena
4. Load the transformed data into Redshift for visualizing and analysis


