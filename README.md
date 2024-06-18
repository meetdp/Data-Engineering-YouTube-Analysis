# Data Engineering: YouTube Analysis 

## Overview

This project aims to build a robust data engineering and analysis pipeline for YouTube videos. It involves securely ingesting data from various sources, transforming it into a suitable format, and storing it in a centralized data lake. Leveraging AWS services, the project ensures scalability and cloud-based processing capabilities. The end goal is to generate insights and create visual dashboards using tools like QuickSight, enabling comprehensive analysis of YouTube video trends based on categories and trending metrics.

## Architecture Diagram
<img src="architecture.jpeg">

## Project Goals
1. Data Ingestion: Build a mechanism to securely ingest data from different sources, specifically focusing on collecting YouTube videos data.
2. ETL System: Develop an Extract, Transform, Load (ETL) system to transform the raw data into a proper format suitable for analysis. This involves structuring and organizing the data for further processing.
3. Data Lake: Establish a centralized data lake, leveraging Amazon S3, to store the YouTube videos data collected from multiple sources. The data lake provides a scalable and secure repository for efficient data storage and retrieval.
4. Scalability: Ensure the system is capable of handling increasing data volumes as the size of the YouTube videos data grows over time. This involves utilizing cloud-based services, such as AWS, to handle the processing and storage requirements effectively.
5. Cloud Computing: Leverage the power of the cloud, specifically AWS, to process and analyze the vast amounts of YouTube videos data. Utilize services like AWS Glue, Lambda, and Athena to perform data integration, computation, and analysis in a scalable and cost-efficient manner.
6. Reporting: Build a dashboard or reporting mechanism to extract valuable insights from the analyzed YouTube videos data. The dashboard should provide answers to specific questions related to video categories and trending metrics, enabling informed decision-making based on the analysis results.

## Services used
1. Amazon S3 (Simple Storage Service): S3 is used as an object storage service to securely store the YouTube videos data. It provides scalability, data availability, security, and high performance for efficient data storage and retrieval.
2. AWS IAM (Identity and Access Management): IAM is used to manage access to AWS services and resources securely. It ensures proper authentication and authorization for the project, allowing controlled access to data and resources.
3. Amazon QuickSight: QuickSight is a scalable and serverless business intelligence (BI) service built for the cloud. It is used in this project to create visual dashboards and perform data analysis on the YouTube videos data, enabling interactive and insightful reporting.
4. AWS Glue: Glue is a serverless data integration service that facilitates the discovery, preparation, and combination of data for analytics and application development. It is utilized in this project to perform data transformation, data integration, and data cataloging tasks.
5. AWS Lambda: Lambda is a serverless computing service that enables running code without the need for managing servers. In this project, Lambda is used to execute Python code for data ingestion and transformation tasks, providing a scalable and cost-effective solution.
6. AWS Athena: Athena is an interactive query service that allows querying data directly from S3 without the need for data loading or infrastructure management. It is employed in this project to perform ad-hoc queries and analysis on the YouTube videos data stored in S3, providing a convenient and efficient way to access the data.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new


