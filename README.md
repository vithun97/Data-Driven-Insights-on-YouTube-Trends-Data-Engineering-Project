# Data Driven Insights on YouTube Trends - Data Engineering Project

## Project Overview:

Our project aims to tackle the challenge of managing and analyzing large amounts of structured and semi-structured YouTube video data. While this may seem like a complex task, we are determined to find solutions that provide meaningful insights into video categories and trending metrics. However, I acknowledge that there may be limitations and obstacles along the way and I am open to constructive criticism to continuously improve my approach.  

## Project Roadmap:  

The objective was to extract insights and trends based on video categories and trending metrics. To achieve this, I implemented a cost-effective and high-performance data lake using **Amazon S3** and **partitioned the data to optimize performance**.

**AWS Glue** was used to create a **catalog** and develop an ETL job that utilized **Spark jobs** and **Amazon SNS** for alerts. Data analysis was conducted using **Athena** and **Spark SQL**, where I wrote SQL queries to uncover valuable insights. To present these insights in a visually appealing manner, I created business intelligence dashboards using **Amazon QuickSight**.

## Project Objectives:

Let's dive into our project objectives and see how we're going to make data analysis and management a breeze!

**1. Ingesting Data with Ease:** We'll be creating a seamless mechanism for collecting data from various sources.  
**2. Transforming Raw Data:** The data we collect will be in raw format, but we'll be using an ETL system to make it usable.  
**3. Centralized Data Repository:** To make data management easier, we'll be storing all data in a centralized data lake.  
**4. Scaling for the Future:** As our data grows, so will our system - we're making sure it's scalable to meet future needs.  
**5. Power of the Cloud:** Processing vast amounts of data on our local computer would be impossible, so we're taking advantage of the cloud with AWS.  
**6. Interactive Reporting Dashboard:** The cherry on top! We'll be building a dashboard to easily get answers to any questions you have about the data.  

## Technologies Used:
**1. Amazon S3:** Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.  
**2. AWS IAM:** This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.  
**3. QuickSight:** Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.  
**4. AWS Glue:** A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.  
**5. AWS Lambda:** Lambda is a computing service that allows programmers to run code without creating or managing servers.  
**6. AWS Athena:** Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.  

## Dataset Used:
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram:
<img src="architecture.jpeg">



