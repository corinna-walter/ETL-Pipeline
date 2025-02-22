# ETL Pipeline

This is my repository for building an ETL Pipeline.

## Introduction
This code will execute the following steps.
- Extract transactional data from a local database
- Identifies and removes duplicates
- Loads the transformed data to a S3 bucket

## Requirements
at least:
- Python 3+
- which libraries are needed, you can find [here](C:\Users\cowa1\Documents\waia-bootcamp\week18\requirements.txt)  


## Step-by-Step Instructions on how to execute the code
- Clone the repository, and change the directory to **etl-pipeline**
- `git clone https://github.com/corinna-walter/etl-pipeline`
- Please contact me for a copy of the local database. otherwise update the file path in the [extract.py](C:\Users\cowa1\Documents\waia-bootcamp\week18\src\extract.py) file accordingly.
- Create a .env file with connection passwords in your **etl-pipeline** -  similar to [this](C:\Users\cowa1\Documents\waia-bootcamp\week18\.env.copy)
- To execute the code to extract, transform and load data to s3, run the `main.py` file:
- Mac users: `python3 main.py`
- Windows users: `python main.py`