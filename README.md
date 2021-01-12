# Data Warehouse of Million Songs Dataset using Airflow, Redshift & S3

This project demonstrates the ETL process automation that can be done using Apache Airflow. Airflow uses DAGs to determine the order of sub-steps oin the whole process. 

# Step to execute

1. Create Amazon Redshift database.

2. Run `create_tables.sql` to create the tables.

3. Run `etl_task.py` to process the entire datasets.
