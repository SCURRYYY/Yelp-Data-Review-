# Yelp-Data-Review-
Thi project is aimed to analyze a subset of Yelp's business, reviews and user data. 
The dataset was obtained from from Kaggle and we will pull this data into a publis s3 bucket: s3://sta9760-yelpdataset/yelp-light/*business.json

With this project, we will explore how Yelp Reviews is distributed? Any skewness? 

## Data

business.json - Contains business data including location, attributes, and categories.
review.json - Review text data including date, stars, and text.
user.json - User data including some compliments that the users made. 

## Install & Setup
Install the packages: pandas, seaborn, keras,and matplotlib. 
The dataset will be read from S3 and loaded as a pyspark dataframe.

## Data Analysis and Visualizations 
The goal is to discover what insights lie hidden in their data.

## Cluster and Notebook Configs
<img width="962" alt="Notebook" src="https://user-images.githubusercontent.com/60529752/81027992-b8aa0e80-8e4d-11ea-8540-0c4faf649fbc.png">
<img width="1048" alt="Cluster" src="https://user-images.githubusercontent.com/60529752/81027999-be9fef80-8e4d-11ea-99a4-2626b737289e.png">

## S3 Bucket
<img width="1047" alt="Buckets" src="https://user-images.githubusercontent.com/60529752/81028217-73d2a780-8e4e-11ea-802d-57b32b7203f7.png">
