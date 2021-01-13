# Data modelling with Cassandra

This repo contains my solution for the Data modelling with Cassandra project of the [Udacity Data Engineering Nanodegree](https://www.udacity.com/course/data-engineer-nanodegree--nd027).

## Purpose

The project involves an imaginary music streaming startup called Sparkify. Sparkify is interested in analytical insights into the streaming habits of the users. Sparkify has songplay event data as CSV files divided per day. The data is derived from the [Million Song Dataset](http://millionsongdataset.com/) [1]. We need to setup a Cassandra database schema and an ETL pipeline to convert these file into a database that is usable for answering analytical queries.

## Code, documentation and output

Please refer to the notebook `Project_1B.ipynb` where everything is included.

## How to run

Please use Jupyter Notebook to run the project file in a Python environment with the following packages installed:

* pandas
* cassandra-driver

Additionally, a Cassandra server must be running, for example using docker:

```
docker run --name cassandra -p 9042:9042 -d cassandra:latest
```

## References

[1] Thierry Bertin-Mahieux, Daniel P.W. Ellis, Brian Whitman, and Paul Lamere. The Million Song Dataset. In Proceedings of the 12th International Society for Music Information Retrieval Conference (ISMIR 2011), 2011.