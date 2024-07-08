# Trending YouTube Video Analysis - Data Engineering Project 

## Overview
This project is designed to efficiently manage and analyze YouTube video data, focusing on video categories and trending statistics. By leveraging a combination of structured and semi-structured data, this initiative aims to provide insightful analytics through robust data engineering practices.

## Project Objectives
- **Data Ingestion**: Develop a system to reliably ingest data from diverse sources.
- **ETL System**: Transform raw data into a structured format suitable for analysis.
- **Data Lake**: Create a centralized repository to accommodate data from multiple sources.
- **Scalability**: Ensure the system can scale effectively as data volume grows.
- **Cloud Integration**: Utilize cloud computing resources to handle large datasets, specifically through AWS services.
- **Data Visualization**: Implement a dashboard for dynamic reporting and analytics.

## Data Architecture 
![Data Architecture](https://github.com/VipulR2796/youtube-trending-videos-analyzer-dateengineering/blob/main/Data_Architecture.png)

## AWS Services Employed
- **Amazon S3**: Utilized for its scalable object storage capabilities, ensuring data availability and security.
- **AWS IAM**: Manages secure access to AWS services and resources.
- **Amazon QuickSight**: Provides scalable and serverless business intelligence services for cloud-based analytics.
- **AWS Glue**: A serverless data integration service that simplifies data discovery, preparation, and integration.
- **AWS Lambda**: Enables code execution without the need to manage servers, facilitating serverless computing architecture.
- **AWS Athena**: Offers an interactive query service that makes data analysis in Amazon S3 using standard SQL efficient and cost-effective.

## Dataset Description
The dataset for this project, sourced from Kaggle, includes daily statistics for up to 200 trending videos per region, spanning several months. Each region's data is stored in separate CSV files, containing details such as video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count. Additionally, a category ID field is included, which varies by region and is stored in a corresponding JSON file.
https://www.kaggle.com/datasets/datasnaek/youtube-new
