# Data Engineering YouTube Analysis Project

# Overview

This project aims to securely manage and analyze YouTube video data based on video categories and trending metrics. It involves collecting structured and semi-structured data from YouTube videos, organizing it, and implementing a categorization module. The system will also analyze trending metrics such as views, likes, and comments. The project aims to provide valuable insights and optimization strategies for YouTube content creators.

# Project Goals

This project involves the following components and goals:

    Data Ingestion: Develop a mechanism to collect data from various sources.
    ETL System: Transform the raw data into a usable format for analysis.
    Data Lake: Create a centralized repository to store and organize the collected data.
    Scalability: Ensure the system can handle growing data volumes effectively.
    Cloud Infrastructure: Utilize AWS for processing and storage requirements.
    Reporting: Build a dashboard for extracting insights and answering key questions.

The above components form a secure and scalable system for data collection, transformation, storage, and analysis, enabling users to derive valuable insights for decision-making.

# In this project, we will utilize the following AWS services:

1. Amazon S3: Scalable object storage for secure and high-performance data storage.
2. AWS IAM: Identity and access management for secure resource access.
3. QuickSight: Serverless business intelligence service for data visualization and analytics.
4. AWS Glue: Serverless data integration for data preparation and combination.
5. AWS Lambda: Scalable compute service for running code without managing servers.
6. AWS Athena: Interactive query service for analyzing data stored in S3.

These services will enable us to securely store, process, analyze, and visualize the collected data with scalability and efficiency.

# Dataset used in the project

The dataset used for this project is sourced from Kaggle. It consists of daily statistics on popular YouTube videos, covering a span of several months. Each file in the dataset corresponds to a specific region and contains information in CSV format. The dataset includes various attributes for each video, such as the video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. Additionally, there is a category_id field specific to each region, which is provided in a linked JSON file. The dataset provides valuable insights into the daily trends of YouTube videos, offering a comprehensive view of video popularity across different regions.
