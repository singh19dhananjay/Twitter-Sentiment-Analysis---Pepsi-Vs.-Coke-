# Twitter-Sentiment-Analysis---Pepsi-Vs.-Coke-
Scraped Twitter to build a dataset by extracting the usernames, tweets, and hashtags by utilizing the "Tweepy" Python library's search API.

Performed Data Cleaning of the tweets by utilizing the "NLTK" and "re" python libraries to remove URLs, emojis, non-English words, etc.

Used the MapReduce functionality to perform twitter sentiment analysis. Got a bag of positive and negative words using nltk.corpus.reader.opinion_lexicon.

Mapper - The output of the mapper gave a (key, value) pair in the format - (username, "coke/pepsi" with sentiment ratio score.

Reducer - The reducer combined the scores for coke and pepsi respectively to give 2 (key, value) pairs in the format - (coke, sentiment score), (pepsi, 
sentiment score).
