# We Rate Dogs Tweet Analysis

An analysis of dog-related tweets from `WeRateDogs` twitter handle [@dog_rates](https://twitter.com/dog_rates).

## Files in Repo:

1. [The analysis notebook](we-rate-dogs-analysis.ipynb).
2. [A summary of data cleaning steps](wrangle_report.ipynb)
3. [Summary of key insights](insights-summary.ipynb)
4. [Folder with data files](data)

## Table of Contents
- [Background](#background)
- [Dataset](#dataset)
- [Packages](#packages)
- [Summary of Process](#summary-of-process)
- [Key Insights](#key-insights)

## Background
##### This project was part of the projects in Udacity's Data Analyst Nano Degree

For every dog lover, their dog is a bundle of joy and cuteness. WeRateDogs are all about loving appreciating, and caring for dogs. They invite people to send them photos of their dogs and in return, they rate the dogs and give funny and witty comments about them. The ratings are x/10, but the ratings are always more than 10 because [they're good dogs Brent](https://twitter.com/dog_rates/status/775410014383026176?lang=en).  
In this project, I aimed to derive insights from the tweet data.

## Dataset
With the help of Udacity, I was able to get access to:
+ Archived tweets (csv) - archive of tweets from 2015-2017
+ Dog breed predictions (tsv) 

Through Twitter's API:
+ Extra tweet data such as likes and retweets (txt) 

## Packages
The analysis was done in Jupyter Notebook. The packages used were:  
| | |
|--- |---|
|re| json|
| Pandas | Numpy 
|Seaborn |Requests
|Matplotlib pyplot|Tweepy|

## Summary of Process
1. Gathering - from all three sources
2. Cleaning - removing unnecessary data and tidying up the rest
3. Analyzing - deriving insights
4. Visualizing - making descriptive plots
## Key Insights
+ The Golden Retriever was the most common dog breed
+ The twitter account had a very active account manager in 2015
+ 2017's tweets the best social media engagement
+ Puppers were the most common dog stage
+ Dog names are almost as many as the owners
