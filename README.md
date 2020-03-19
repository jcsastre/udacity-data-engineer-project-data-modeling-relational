# Project 1 - Data Modeling with PostgreSQL 

## Introduction

The company Sparkify needs to get insights from the log files based on the users using his app. In this
case they are interested in analyze what songs users are listening to. Becasue the log data in his current
format is not easy to analyze, the need to implement an ETL process to generate one fact table and some dimensional tables. This kind of star schema database is very suitable for analytics purposes.

## How to run the Python scripts

First, to create the database:
```bash
python create_tables.py
```

Then, to execute the ETL process:
```bash
python etl.py
```

## Files in the repository

```
.
├── create_tables.py       Python script that initializes the database and creates the schema.
├── data/                  Folder containing log files.
├── etl.ipynb              Jupyter notebook used to prototype ETL process.
├── etl.py                 Python script based on the ETL notebook and that executes complete ETL process.
├── sql_queries.py         Python file containing SQL statements used by the code of the other script files.
└── test.ipynb             Jupyter notebook used to check the content of the database tables.
```