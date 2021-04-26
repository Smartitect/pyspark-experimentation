# pyspark-experimentation
Set up to enable me to play with local implementation of PySpark.

## Pre-requisites

You need to have the following installed to run this notebook:

- Java
- Python
- Apache Spark
- winutils.exe

You also need to set up two environment variables:

- `SPARK_HOME` for example `set SPARK_HOME=C:\spark\spark-3.1.1-bin-hadoop2.7`
- `HADOOP_HOME` for example `set HADOOP_HOME=C:\spark\spark-3.1.1-bin-hadoop2.7\hadoop`

More detailed instructions about all of the above, are provided in the following article:

https://towardsdatascience.com/installing-apache-pyspark-on-windows-10-f5f0c506bea1

**In addition**, you also need to set up third environment variable as follows:

`set PYSPARK_PYTHON=python`

## Running this project locally

Clone the repository locally.

At the command prompt, from the root of the project, initialise the Python virtual environment and install dependencies:

`pipenv install`

To run unit tests:

`pipenv run pytest`
