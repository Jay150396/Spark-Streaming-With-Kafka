# Spark-Streaming-With-Kafka
Spark Streaming of RSVPs from meetup.com API using Kafka meetup.com provides a streaming data of RSVPs in JSON Format. The stream is accesible through, http://stream.meetup.com/2/rsvps

Getting this streaming data into Apache Spark-Streaming is the first step to perform various analytics, recommendations or visualizations on the data.

# Technologies Used
- Kafka 2.8
- Spark 2.4.5
- Data Feeds: Kafka
- ETL: Spark DataFrame, Spark Structured Streaming
- Data Storage: Hdfs, S3
- Resource Management: Yarn
- Kafka Python API is used to interact with kafka cluster. PySpark is used to write the spark streaming jobs.
