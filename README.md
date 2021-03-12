# Wrangle-and-Analyze-Data-WeRateDogs

Project Outline:

1. Data wrangling:<br>
Gathering data<br>
Assessing data<br>
Cleaning data<br>

2. Storing, analyzing, and visualizing your wrangled data

3. Reporting

Introduction:

In this project, we are going to gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it anf finally act on it through analysis, visualization and/or modeling using Python (and its libraries) and/or SQL.

The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs.

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The Twitter archive of WeRateDogs contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. Of the 5000+ tweets, we have filtered for tweets with ratings only because not all 5000+ tweets are dog ratings and some are retweets. So there are about 2356 tweets.

The data was extracted programmatically from each tweet's text, but the ratings as well as dog names and dog stages probably aren't all correct. So, we'll need to assess and clean these columns in order to use them for analysis and visualization. There is also additional data, which include retweet count and favorite count, can be also gathered programmatically from Twitter's API using Tweepy Library in Python

After having ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs, the output is a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

1. Data wrangling

Our next step is that all of this additional data will need to be gathered, assessed, and cleaned.

Step 1. Gathering Data:
The first step in our data wrangling process is gathering data from several different sources and file formats such as:

The WeRateDogs Twitter Archive, which is a cvs file that contains the tweet for each dog's name, its rating and stage.
The Tweet Image Prediction, which is what breed of dog is in each tweet according to a neural network.
The Twitter's API and JSON data, which will be used to gather retweet count and favorite count ( two missing columns in the Twitter Archive).

Step 2. Assessing Data:

After gathering data, the 3 tables which are twitter_archive, image_prediction and tweet_json were saved and assessed visually and programmatically to identify data quality issues as well as tidiness is-sues.

Step 3. Cleaning Data:

Cleaning data is the third step in data wrangling process. We are going to fix the quality and tidiness issues that we have identified in the assess step.

2. Storing, analyzing, and visualizing the wrangled data

The next step is to start analysing and visualizing our dataset, and then drawing any valuable conclu-sions.

3. Reporting:<br>
- Act_report
- Wrangled_report


