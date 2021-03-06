# TwitterAnalysis

Twitter Analysis using PySpark and Jupyter(Visualization). Performs Statistical and Sentimental Analysis on tweets. Tweepy Python Library is used for accessing Twitter API.

# Apache Spark

Refer: https://spark.apache.org/downloads.html

# Tweepy

Refer: https://tweepy.readthedocs.io/en/v3.5.0/

# Twitter Keys

Refer: https://www.slickremix.com/docs/how-to-get-api-keys-and-tokens-for-twitter/

# Twitter Data

Refer: https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/intro-to-tweet-json.html

• Fetches most popular tweet topics in a location using trends_place(id)

• Id : WOEID (Where On Earth IDentifier) which is a unique eference identifier assigned by Yahoo!

• Retrieves the top most popular tweet topic based on tweet_volume

• Fetched tweets on the most popular topic

• Performs Statistical Analysis on that topic :
  
  - Retrieve top most popluar hashtags 
 
  - Retrieve top retweeted tweets
  
  - Retrieve top liked tweets

• Perform Sentimental Analysis :
  
  - Analyse Positive and Negative Tweets on topic
