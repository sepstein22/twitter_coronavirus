# Coronavirus twitter analysis


**Learning Objectives:**

1. work with large scale datasets
1. work with multilingual text
1. use the MapReduce divide-and-conquer paradigm to create parallel code

## Background

Twitter is an incredibly powerful form of communication. With over 330 million active users, the twitter platform enables direct communication of many people around the world. Each second, on average, 6,000 tweets are made. This sums to 500 million tweets a day and 200 billion a year. Approximately 1% of these tweets are geotagged. This means the location of the user’s device at the time of the tweet is included, providing a geographical location of where the tweet originated from. As a means of communication, Twitter has become a popular platform for discussing current events, including the topic of coronavirus.

## Project Overview

The dataset consisted of all geotagged tweets sent in 2020. The aim of this project, in the broadest sense, is to monitor the spread of coronavirus discourse on social media. Using the MapReduce procedure to visualize the data, the use of hashtags for languages and countries was tracked, a language dictionary and country dictionary was created, and the total number of occurrences for each hashtag was tracked.

This code could be generalized to analyze twitter data, by changing the hashtags explored. This would involve editing the `src/map.py` and viz commands. The `src/reduce.py` program will similarly merge all outputs from the `src/map.py`. 


