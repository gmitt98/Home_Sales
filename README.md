# Home_Sales

Languages and technologies used:
- Python 3.9.12
- Spark
- SQL

## Repository contents

This repo contains our Jupyter Notebook code (Home_Sales)
The data used are accessed from a link to an S3 bucket

## Purpose

This project tested different ways of connecting to the data and querying the data using SQL in Spark.
We tested uncached tables, cached tables, and Parquet files

## Results

We found the following query times, in seconds:

| Uncached  | Cached  |  Parquet |
|---|---|---|
|  1.06 | 0.86  | 0.62  |