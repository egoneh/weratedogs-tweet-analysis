## Introduction
This project aims to wrangle, analyze, visualize and gain insight into WeRateDogs tweet data.
WeRateDogs is a Twitter account that rates people's dogs with humorous comments about the dog.

## Dataset
This project uses 3 datasets:
1. Twitter archive enhanced: This is a CSV dataset that was provided by Udacity. It holds the WeRateDogs Twitter archive and provides most of the data needed for this project.
2. Image prediction dataset: This is a TSV dataset that results from a neural network classifying the images in Twitter archive data.
3. Supplementary Twitter API JSON dataset: This dataset is to be obtained from Twitter API using the Tweepy library. Due to difficulty in obtaining approval for Twitter API, the copy that was provided by Udacity was used for this study.

## Data Assessment
The datasets were visually assessed by loading them into Microsoft excel and visual studio code as text files. The visual assessment was conducted to quickly develop a mental image of the structure of the dataset and identify quality and tidiness issues that can be uncovered by visual assessment. Next, the data frame was assessed programmatically by loading it into pandas data frame and executing functions to establish the shape of the dataset, column names, length, data types, row count and identify quality and tidiness issues. Some pandas
functions used during assessment: `info`, `describe`, `isnull`, `sum`, `value_counts`, `head`, `sample`, `duplicated` e.t.c.