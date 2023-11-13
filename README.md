# mongodb-change-stream
one way data synchronization mongodb to azure sql whatever changes made in mongordb database will be synchronize with azure sql in real time.
-------------------------------------------------------------------------------------------------------------------------------
Prerequisites:
•	MongoDB on Atlas
•	Databricks cluster for Spark Streaming
•	Azure blob container
•	Azure SQL database
-------------------------------------------------------------------------------------------------------------------------------
Databrick cluster:-
• spark version: 10.4 LTS (includes Apache Spark 3.2.1, Scala 2.12)
• spark connctor jar(mavan): org.mongodb.spark:mongo-spark-connector_2.12:10.2.0
-------------------------------------------------------------------------------------------------------------------------------
