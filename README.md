# mongodb-change-stream
One-way data synchronization between Azure SQL and MongoDB. Any modifications made to the mongodb database will instantly synchronize with Azure SQL.
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
Note: 
• Create a sql table with the same name as the mongodb collection.
• The mongodb document's field name and the column name in a sql table must match.
