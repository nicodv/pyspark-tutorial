# pyspark-tutorial
A short tutorial notebook on PySpark

Prerequisites
-------------

- If you do not have it already, you will need the JDK available [here](http://www.oracle.com/technetwork/java/javase/downloads/index.html).

- Download a pre-built version of Spark from [here](https://spark.apache.org/downloads.html) and unpack it.

- Set the following environment variables, for example in your `~/.bash_profile`:

    `export JAVA_HOME=$(/usr/libexec/java_home)`
    
    `export SPARK_HOME=/PATH/TO/SPARK`
    
    `export PYTHONPATH=/PATH/TO/SPARK/python`

- If you want Spark to work with a specific Python version/virtualenv, also set this one:

    `export PYSPARK_PYTHON=/PATH/TO/PYTHON/INSIDE/VIRTUALENV`

- Install Py4j dependency:

    `pip install py4j`
