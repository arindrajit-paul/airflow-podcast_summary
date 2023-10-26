# Airflow Data Pipeline for Downloading Podcasts

[Airflow](https://airflow.apache.org/) is a popular Python-based data engineering tool for running flexible and powerful data pipelines. This project utilized Airflow to download podcast episodes (source: Marketplace).

The project contains 3 key steps - 
1. Creating a pipeline to download and parse the podcast episode metadata.
2. Creating a sqlite database to store the metadata.
3. Creating a pipeline to downlaod the podcasts on the local machine.

Airflow can help in achieving the following - 
- Ability to schedule the project to run daily to get new podcasts when they go live.
- Each step can run independently, which makes it easier to debug.
- Ability to parallelize the steps and run them in the cloud. 

The goal of this project was to get started with buidling data pipelines with Airflow, with multiple options to expand upon it by adding more pipelines.

## Required libraries and packages
- Python (3.8 and above)
- Airflow (2.3 and above)
- Pandas
- sqlite3
- xmltodict
- requests

**Upcoming addition:** Add a new task to transcribe the podcast episodes (speech-to-text).