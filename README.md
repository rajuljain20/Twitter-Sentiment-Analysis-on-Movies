#Twitter Sentiment Analysis using Python

Using tweepy(python client for the official twitter API) I have extracted tweets from IMDB page of Twitter.
Data is extracted using web scraping technique.

#File Description

##IMDB_tweet_Extractor.ipynb

This file contains the code used for extracting real time rating data from IMDB webpage of twitter.
All the movie ratings along with user tweet id and timestamp when tweet was posted is etracted in Tweet_ratings.csv file

##backbone.py

Backup code for IMDB_tweet_Ex

##Twitter_Wordcloud_most_used_hashtags.ipynb

This file fetches streaming tweets related to a topic you specify. For this project, I have made use of keywords like:
black panther’,’ready player one’,’pacific rim’,’justiceleague’,’coco’,’gringo’,’rampage’ for col- lecting tweets
This file streams real time tweets for these specific words and forms wordcloud for most used hash tagged words.

##Project One.ipynb

Explains intricate details of how entire database is formed.

##Brief description of the tables used in database-

Movies-        Contains data related to movie name, genres and year of release
Ratings-       This data is picked from existing Grouplens database has has movie ratings from 0-5 scale
Tag-           Contains all the real time hashtags extracted from IMDB page of twitter
Tweet_ratings- Conatains all the ratings of movies posted on IMDB page of twitter


