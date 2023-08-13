Apache Spark
Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

https://spark.apache.org/

Jenkins Build AppVeyor Build PySpark Coverage

Online Documentation
You can find the latest Spark documentation, including a programming guide, on the project web page. This README file only contains basic setup instructions.

Building Spark
Spark is built using Apache Maven. To build Spark and its example programs, run:

./build/mvn -DskipTests clean package
(You do not need to do this if you downloaded a pre-built package.)

You can build Spark using more than one thread by using the -T option with Maven, see "Parallel builds in Maven 3". More detailed documentation is available from the project site, at "Building Spark".

For general development tips, including info on developing Spark using an IDE, see "Useful Developer Tools".

Interactive Scala Shell
The easiest way to start using Spark is through the Scala shell:

./bin/spark-shell
Try the following command, which should return 1,000,000,000:

scala> spark.range(1000 * 1000 * 1000).count()
Interactive Python Shell
Alternatively, if you prefer Python, you can use the Python shell:

./bin/pyspark
And run the following command, which should also return 1,000,000,000:

>>> spark.range(1000 * 1000 * 1000).count()
Example Programs
Spark also comes with several sample programs in the examples directory. To run one of them, use ./bin/run-example <class> [params]. For example:

./bin/run-example SparkPi
will run the Pi example locally.

You can set the MASTER environment variable when running examples to submit examples to a cluster. This can be a mesos:// or spark:// URL, "yarn" to run on YARN, and "local" to run locally with one thread, or "local[N]" to run locally with N threads. You can also use an abbreviated class name if the class is in the examples package. For instance: