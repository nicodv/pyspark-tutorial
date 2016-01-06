# pyspark-tutorial
A short tutorial notebook on PySpark

Prerequisites
-------------

- Install Java 7 or newer on your OS.

- Download a pre-built version of Spark from [here](https://spark.apache.org/downloads.html) and unpack it.

- Set the following environment variables, for example in your `~/.bashrc`:

    `export SPARK_HOME=/PATH/TO/SPARK`
    
    `export PYTHONPATH=/PATH/TO/SPARK/python`

- If you want Spark to work with a specific Python version/virtualenv, also set this one:

    `export PYSPARK_PYTHON=/PATH/TO/PYTHON/INSIDE/VIRTUALENV`

- Install Py4j dependency:

    `pip install py4j`
