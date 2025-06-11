# Stock-market-real-time-pipeline
End to End Stock Market Real Time Data Engineering Project

# Introduction 
This project demonstrates an end to end data engineering pipeline for processing real-time stock market data using Apache Kafka. the pipeline ingests stock market data, streams it through kafka, stores it in Amazon S3, and enables querying and analysis using AWS Glue and AWS Athena. the focus is on building a robust data pipeline to handle real-time data processing, showcasing key data engineering concepts and tools.

# Project Architecture
![Architecture](https://github.com/user-attachments/assets/e1fb3ef3-e351-42c2-9e1f-ac6df1fb10c7)


# Technologies Used
• Python: For scripting the producer and consumer logic.

• Apache Kafka: For real-time data streaming.

• Amazon Web Services (AWS):
   EC2: To host the Kafka server.
   S3: For storing streamed data.
   Glue: For cataloging data.
   Athena: For querying and analyzing data.

• SQL: For querying data in AWS Athena.

# Acknowledgments
 • Created by Darshil parmar github-https://github.com/darshilparmar
 
 • Inspired by real-world data engineering challenges in financial data processing.
 
 • Thanks to the open-source community for tools like Apache Kafka and AWS services.
