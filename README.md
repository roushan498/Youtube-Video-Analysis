# Youtube-Video-Analysis
📌 Overview

This project focuses on securely managing, processing, and analyzing structured and semi-structured YouTube trending video data. The analysis is performed based on video categories and trending performance metrics to extract meaningful insights.

The solution is designed to build a scalable, cloud-based data pipeline capable of handling growing datasets efficiently.

🎯 Project Goals
1️⃣ Data Ingestion

Develop a robust mechanism to collect data from multiple sources in a structured manner.

2️⃣ ETL Pipeline

Since the incoming data is in raw format, implement transformation processes to clean, standardize, and convert it into an analytics-ready format.

3️⃣ Data Lake Architecture

Create a centralized repository to store data from various sources, ensuring organized and efficient data management.

4️⃣ Scalability

Design the system to handle increasing data volumes without performance degradation.

5️⃣ Cloud Implementation

Leverage cloud infrastructure to process large-scale datasets efficiently. In this project, AWS is used as the cloud platform.

6️⃣ Reporting & Visualization

Develop interactive dashboards to answer key analytical questions and generate actionable insights.

🛠️ AWS Services Used
🔹 Amazon S3

An object storage service that provides high scalability, durability, security, and performance. It acts as the central data lake for storing raw and processed data.

🔹 AWS IAM

Identity and Access Management service used to securely control access to AWS resources and services.

🔹 Amazon QuickSight

A scalable, serverless, cloud-native Business Intelligence (BI) tool used to build interactive dashboards and visual reports.

🔹 AWS Glue

A serverless data integration service used for data discovery, transformation, and preparation for analytics and machine learning.

🔹 AWS Lambda

A serverless compute service that enables execution of code without provisioning or managing servers.

🔹 AWS Athena

An interactive query service that allows querying data directly from Amazon S3 using SQL, without loading it into a database.

📂 Dataset Used

The project uses a Kaggle dataset containing daily statistics of trending YouTube videos across multiple regions.

Dataset Features Include:

Video Title

Channel Title

Publication Time

Tags

Views

Likes & Dislikes

Description

Comment Count

Category ID (region-specific JSON file)

Each region’s trending data is stored in separate CSV files, with up to 200 trending videos recorded per day across several months.

🔗 Dataset Link:
https://www.kaggle.com/datasets/datasnaek/youtube-new
