# Microsoft Azure HDInsight Playground


[Azure HDInsight](https://azure.microsoft.com/en-gb/services/hdinsight/) is a fully managed, full-spectrum, open-source analytics service for enterprises. HDInsight is a cloud service that makes it easy, fast, and cost-effective to process massive amounts of data. HDInsight also supports a broad range of scenarios, like extract, transform, and load (ETL); data warehousing; machine learning; and IoT.

Use Azure HDInsight to analyze streaming or historical data.

<b>Productivity</b> <BR>
Azure HDInsight enables you to use rich productive tools for Hadoop and Spark with your preferred development environments. These development environments include Visual Studio, VSCode, Eclipse, and IntelliJ for Scala, Python, R, Java, and .NET support. Data scientists can also collaborate using popular notebooks such as Jupyter and Zeppelin.


<b>[Azure HDInsight Documentation](https://docs.microsoft.com/en-us/azure/hdinsight/)</b>

<b>[Scenarios for using HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction#scenarios-for-using-hdinsight)</b>
* Batch processing (ETL)
* Data warehousing
* Internet of Things (IoT)
* Data science
* Hybrid

<b>[Cluster types in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction#cluster-types-in-hdinsight)</b> <BR>
HDInsight includes specific cluster types and cluster customization capabilities, such as the capability to add components, utilities, and languages. HDInsight offers the following cluster types:
* Apache Hadoop: A framework that uses HDFS, YARN resource management, and a simple MapReduce programming model to process and analyze batch data in parallel.
* Apache Spark: An open-source, parallel-processing framework that supports in-memory processing to boost the performance of big-data analysis applications. See What is Apache Spark in HDInsight?.
* Apache HBase: A NoSQL database built on Hadoop that provides random access and strong consistency for large amounts of unstructured and semi-structured data--potentially billions of rows times millions of columns. See What is HBase on HDInsight?
* ML Services: A server for hosting and managing parallel, distributed R processes. It provides data scientists, statisticians, and R programmers with on-demand access to scalable, distributed methods of analytics on HDInsight. See Overview of ML Services on HDInsight.
* Apache Storm: A distributed, real-time computation system for processing large streams of data fast. Storm is offered as a managed cluster in HDInsight. See Analyze real-time sensor data using Storm and Hadoop.
* Apache Interactive Query preview (AKA: Live Long and Process): In-memory caching for interactive and faster Hive queries. See Use Interactive Query in HDInsight.
* Apache Kafka: An open-source platform that's used for building streaming data pipelines and applications. Kafka also provides message-queue functionality that allows you to publish and subscribe to data streams. See Introduction to Apache Kafka on HDInsight.


<b>[Open-source components in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction#open-source-components-in-hdinsight)</b> <BR>
Azure HDInsight enables you to create clusters with open-source frameworks such as Hadoop, Spark, Hive, LLAP, Kafka, Storm, HBase, and R. These clusters, by default, come with other open-source components that are included on the cluster such as Ambari, Avro, Hive, HCatalog, Mahout, MapReduce, YARN, Phoenix, Pig, Sqoop, Tez, Oozie, ZooKeeper.

<b>[Programming languages in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction#programming-languages-in-hdinsight)</b>
* Java
* Python

<b>[Development tools for HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-introduction#development-tools-for-hdinsight)</b>
* Azure toolkit for IntelliJ
* Azure toolkit for Eclipse
* Azure HDInsight tools for VS Code
* Azure data lake tools for Visual Studio

<b>[Hadoop components available with different HDInsight versions](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-component-versioning?toc=%2Fen-us%2Fazure%2Fhdinsight%2Fhadoop%2FTOC.json&bc=%2Fen-us%2Fazure%2Fbread%2Ftoc.json#hadoop-components-available-with-different-hdinsight-versions)</b>

<b>[HDInsight Windows retirement](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-component-versioning?toc=%2Fen-us%2Fazure%2Fhdinsight%2Fhadoop%2FTOC.json&bc=%2Fen-us%2Fazure%2Fbread%2Ftoc.json#hdinsight-windows-retirement)</b> <BR>
Microsoft Azure HDInsight version 3.3 was the last version of HDInsight on Windows. The retirement date for HDInsight on Windows is July 31, 2018. 

<b>[HDInsight Python Management SDK Preview](https://docs.microsoft.com/en-gb/python/api/overview/azure/hdinsight?view=azure-python)</b>

<b>[HDInsight Java Management SDK (Preview)](https://docs.microsoft.com/en-gb/java/api/overview/azure/hdinsight?view=azure-java-preview)</b>

<b>[Machine learning on HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-machine-learning-overview?toc=%2Fen-us%2Fazure%2Fhdinsight%2Fhadoop%2FTOC.json&bc=%2Fen-us%2Fazure%2Fbread%2Ftoc.json)</b> <BR>
There are several machine learning options in HDInsight: SparkML and MLlib, R, Hive, and the Microsoft Cognitive Toolkit.

<b>[Deep dive - advanced analytics](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-deep-dive-advanced-analytics)</b>


# Tutorials
<b>[Tutorial: Extract, transform, and load data using Apache Hive on Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-analyze-flight-delay-data-linux?toc=%2Fen-us%2Fazure%2Fhdinsight%2Fhadoop%2FTOC.json&bc=%2Fen-us%2Fazure%2Fbread%2Ftoc.json)</b>

<b>[Walkthrough: Scoring a trained CNTK model with PySpark on a Microsoft Azure HDInsight cluster](https://github.com/Azure-Samples/hdinsight-pyspark-cntk-integration)</b>

<b>[Data Science Quickstart with the Iris Dataset](https://notebooks.azure.com/liwong/libraries/iris1234/html/Data+Science+Quickstart.ipynb)</b>

<b>[Azure Code Samples for HDInsight](https://azure.microsoft.com/en-us/resources/samples/?service=hdinsight&sort=0)</b>

<b>[Using Impala with the Azure Data Lake Store](https://www.cloudera.com/documentation/enterprise/5-14-x/topics/impala_adls.html)</b>

<b>[SQL Engines for Hadoop: Hive vs Impala vs Spark](http://bigdata.black/infrastructure/sql-engines-hadoop-hive-spark-impala/)<b>

<b>[Leveraging Hive with Spark using Python](https://datascienceplus.com/leveraging-hive-with-spark-using-python/)</b>

<b>[The Big Data Showdown: Apache Spark vs Impala](https://learning.naukri.com/articles/spark-vs-impala/)</b>

<b>[Importing Data into Hive Tables Using Spark](http://www.informit.com/articles/article.aspx?p=2756471&seqNum=5)</b>

<b>[Use portal to create an Azure Active Directory application and service principal that can access resources](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-create-service-principal-portal)</b>

<b>[Reading and Writing the Apache Parquet Format](https://arrow.apache.org/docs/python/parquet.html)</b>

<b>[How to Convert CSV to Parquet Files?](http://blogs.quovantis.com/how-to-convert-csv-to-parquet-files/)</b>

<b>[Introduction to DataFrames - Python](https://docs.databricks.com/spark/latest/dataframes-datasets/introduction-to-dataframes-python.html)</b>

<b>[Spark SQL, DataFrames and Datasets Guide](https://spark.apache.org/docs/latest/sql-programming-guide.html)</b>

<b>[Install the Azure Toolkit for Eclipse](https://docs.microsoft.com/en-gb/java/azure/eclipse/azure-toolkit-for-eclipse-installation?view=azure-java-stable)</b>

<b>[Use Azure Toolkit for Eclipse to create Spark applications for an HDInsight cluster](https://docs.microsoft.com/en-gb/azure/hdinsight/spark/apache-spark-eclipse-tool-plugin)</b>

<b>[Use Sqoop with Hadoop in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-use-sqoop)</b>

<b>[Use Microsoft Cognitive Toolkit deep learning model with Azure HDInsight Spark cluster](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-microsoft-cognitive-toolkit)</b>


<b>[Use the Beeline client with Apache Hive](https://docs.microsoft.com/en-gb/azure/hdinsight/hadoop/apache-hadoop-use-hive-beeline)</b>

<b>[Create Hive tables and load data from Azure Blob Storage](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/move-hive-tables)</b>

<b>[Upload data for Hadoop jobs in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-upload-data#commandline)</b>

<b>[Hadoop Commands](http://hadoop.apache.org/docs/r2.7.0/hadoop-project-dist/hadoop-common/FileSystemShell.html#copyFromLocal)</b>

<b>[Hadoop commnads by Caio](https://github.com/caiomsouza/pentaho-big-data-guides-and-sample-code/tree/master/guides)</b> 
  
  

