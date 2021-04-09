# Sentiment Analysis over Tesla's Cybertruck realease, from twitter data
Problem: a company wants to know the sentiment over a new product right after the release.

Why is this usefull: This can be usefull to do pre-releases, feel the overall sentiment about the product over the internet and do the needed changes if needed. Also for after releases to predict how well the sales are going to be or to find insights to chages of product, comunication etc

Tech:

Webscrapping via API or not
NPL
Tasks/Brundown:

Get data from twitter from 2 days after the realease of Tesla's Cybertruck. It was released on november 21, 2019
Run a sentiment analysis over the tweets
Determine the overall sentiment about the product and give insights about possible changes on the product, future comunication, marketing etc
Day 1 - 11/03/2021: I tryed to find the best library to get the tweets. tweepy was the first attempt via twitter API, but I couldn't figure it out how to filter by the tweet date, so I used snscrape that web scrapes twitter and other social medias. Figure it out how to get the tweets based on words and dates
Day 2 - 12/03/2021: Clean the tweet for analysis, run sentiment analysis on the model with TextBlob. Took a while to figure it out the right functions to clean the tweets.
Day 3 - 15/03/2021: Adapted the model to only english tweets. Realized filtering tweets by only one word can return too many tweets that has no relation to the feel of the product, so to be more assertive, I ran with "cybertruck" and "looks", with this we can take more insights for example, to the design area etc
Day 4 - - Find the most used words so we can have an idea of the context for the positive/negative tweets
