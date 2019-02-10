# SparkTutorial

Assumes that jupiter notebook is integrated with PySpark
Works on StandAlone  Spark


You need to following set in bash_profile 
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_191.jdk/Contents/Home
export SPARK_HOME=/Users/<username>/spark-install/spark-2.4.0-bin-hadoop2.7
export PATH=$SPARK_HOME/bin:$PATH

# Py Spark set up for Jupyter
export PYSPARK_DRIVER_PYTHON='jupyter'
export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
export PATH=/usr/local/scala/bin:$PATH

Launches with Jupyter with typing pyspark on shell.

