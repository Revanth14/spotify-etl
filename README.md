# spotify-etl
Spotify end-to-end pipeline
## Business objective:
As we all know, the goal of every data project is to generate value for the business, hence we are collecting different types of data for generating insights. Also, develop and implement pipelines that extract, transform, and load data into a product that helps the organization reach its strategic goals.
In this project, Data was collected from Spotify’s API and spotipy library. This data gives the top 50 global songs. (ranked weekly)
## Overview:
The project extracts diverse data from the Spotify API, including artists, albums, and songs from a specified playlist, and stores it in AWS Simple Storage Service (S3) for analysis in AWS Athena. The ultimate goal is to establish an automated pipeline hosted on AWS for data extraction and processing.
## Services Used:
1.	Spotify API
2.	AWS IAM
3.	AWS S3
4.	AWS Lambda functions
5.	AWS Athena
6.	AWS Glue
7.	Python

## Project Flow
1.Integrating with Spotify API and extracting Data using Python
2.Deploying code on AWS Lambda for Data Extraction
3.Adding trigger to run the Lambda function for extraction automatically
4.Writing transformation function
5.Building automated trigger on transformation function
6.Store files on S3 properly
7.Building Analytics Tables on data files using Glue and Athena

## Packages used
1. pip install pandas
2. pip install numpy
3. pip install spotipy
