# Big Data Sentiment Analysis on Demonetisation using PIG

## ABSTRACT
This project addresses the problem of sentiment analysis in twitter;
that is classifying tweets according to the sentiment expressed in them: positive, negative or neutral.

Twitter is an online micro-blogging and social-networking platform which allows users to write short status updates of maximum length 140 characters. It is a rapidly expanding service with over 200 million registered users out of which 100 million are active users and half of them log on twitter on a daily basis -generating nearly 250 million tweets per day. Due to this large amount of usage we hope to achieve a reflection of public sentiment by analysing the sentiments expressed in the tweets.
 
Analysing the public sentiment is important for many applications such as firms trying to find out the response of their products in the market, predicting political elections and predicting socioeconomic phenomena like stock exchange. 

The aim of this project is to develop a functional classifier for accurate and automatic sentiment classification of an unknown tweet stream.

## SUMMARY
I am doing Sentiment Analysis on Demonetization across India by using data from twitter. For fetching the twitter data we can either use Apache Flume or download the available dataset from the internet.

After Fetching the data from twitter, it would be loaded directly to HDFS( Hadoop Distributed File System). This way we can reduce the extra overhead of transferring the data from local system to HDFS.
Next step deals with using the dictionary file to score the sentiment of each tweet by the number of positive words compared to number of negative words and then assigned a positive,negative or neutral sentiment value to each tweet. 

At last I have generated the positive tweets and negative tweets and stored or loaded the results back to HDFS( Hadoop Distributed File System)

## REFERENCES
www.acadgild.com

