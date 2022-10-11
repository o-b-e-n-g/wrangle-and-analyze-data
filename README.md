# Wrangle and Analyze data
 A Project aimed at wrangling (and analyzing and visualizing) a tweet archive of a Twitter account


## Introduction

Data obtained from three sources below were wrangled to obtain clean and merged into one dataset.

1. A **twitter_archive_enhanced.csv** file which was provided directly by Udacity and downloaded directly into the working environment.
2. An **image predictions.csv** file which is hosted on Udacity's servers and was downloaded programmatically using the Requests library.
3. Twitter, using Python's Tweepy library to query the Twitter API for each tweet's retweet count and favorite ("like") count at the minimum. The tweet IDs in the **twitter_archive_enhanced.csv** file were used for the query and the results were stored in a tweet.json.txt file

The resulting dataset was analysed to identify the following:
- The most popular dog names
- The source used most for tweeting
- The breed favorited the most
- The month in which most tweets were made



## Insights

We obtained the various insights from our exploration:
1. The most popular dog names are Charlie, Lucy, Cooper and Oliver
2. The twitter app was the most used source for tweets
3. The most favorite dog breed was the Golden Retriever which was favourited a total of 1,106,547 times
4. Most tweets were made between the months of November to January which is generally a holiday period. This possibly indicates that most people were able to engage the tweets because when they were more free, with breaks from works
