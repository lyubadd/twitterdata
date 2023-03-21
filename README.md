# twitterdata

Introduction

This Data Wrangling student project analyzes Twitter data from the WeRateDogs account.

It aims to answer the following two research questions:

1. Which are the top 10 dog breeds:
- based on the WeRateDogs official account ratings?
- based on follower retweets and likes?
- Is there any overlap between the top 10 breeds according to the WeRateDogs official rating and follower engagement (retweets and likes)?

2. Are the 'retweet' and 'like' rates correlated?

The analysis uses the following three datasets:

First, an enhanced Twitter archive: the WeRateDogs Twitter archive containing basic tweet data for all of the account's 5000+ tweets, but there may be 
errors in the ratings, the dog names and the dog stages.

Second, an image predictions file: the image predictions created through a neural network that can classify dog breeds alongside each tweet ID, image URL, 
and the image number that corresponds to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

Third, additional Data via the Twitter API: query of Twitter's API to gather the retweet count and the favorite count.

The project is organized in four sections:

Data gathering
Data assessment
Data cleaning
Data analysis and visualization

Conclusions

- The most appreciated dog breed taking all rating metrics into account is the saluki.
- The most appreciated dog breed according to the official WeRateDogs rating is the clumber.
- The most appreciated dog breed according to total follower engagement (likes+ retweets) is the Bedlington terrier.
- There is almost no overlap between the top 10 breeds according to the official WeRateDogs ratings and according to follower engagement (likes + tweets).
- The 'retweet' and 'like' rates are positively correlated.

The WeRateDogs channel has started a foundation called 15outof10 to help dogs that are less likely to be adopted. If you want to learn more and support 
them, check out 15outof10.org
