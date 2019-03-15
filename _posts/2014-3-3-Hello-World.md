---
layout: post
title: Blog Post 1
published: true
---
## Introduction ##


Hello! 

This is the first blog post for Brown University's CS1951a Data Science Final Project.

The students in our project group are:
Jack Kates, Julia Windham, Leo Ryu, Nam Do, and Sandra Ha. 

## Vision ##

One of the greatest problems driving apart modern society is the bitter divide between political parties. Bipartisian dialogue gets drowned beneath the name-calling, insult-tossing, and tantrum-throwing antics of members on both sides of the political spectrum. 

Our goal for the final project is to use Twitter data in order to ascertain public sentiment about various political issues. By doing so, we hope to discover which political issues create the most volatile impact amongst the general population. 

## Data ##
Our method of collecting data for this project is two fold. 

The first is using tweets from the publically available datasets found [here](https://data.world/bkey/politician-tweets). One dataset contains tweets made by various politicians, and the second dataset contains tweets containing political information.

The second is using the Twitter API to streams real time tweets that contain a specific keyword. For example, we can use the API to stream 1000 tweets containing the word "debt". By streaming tweets based on keywords, we hope to collect tweets that accurately represent current public sentiment. 

## Plan for Analysis ##

Our approach for analyzing the data is using a tweet's retweet count to judge it's "polarity"-- the intuition being a controversial tweet will have a high number of retweets. By doing so, we can then begin comaparing each issue against one another and rank an issue based on its polarity value. 
