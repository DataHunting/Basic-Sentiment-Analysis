# Basic-Sentiment-Analysis: 
Using Naive Bayes estimator to classify movie reviews as positive or negative.

nltk is the most popular Python package for Natural Language Processing, it provides algorithms for importing, cleaning, pre-processing text data in human language and then apply computational linguistics algorithms like sentiment analysis.

Analysis 1

This program uses the movie_reviews dataset from nltk's corpus, consisting of 2000 reviews marked as positive and negative. A bag-of-words is created for 2000 most common words that occur over the vocabulary of the entire corpus. And each review is represented by a hot-coded feature vector of those 2000 words. A basic sentiment analysis is carried out with nltk's built-in Naive Bayes estimator with a 80-20% split between training and test data.

Analysis 2

This program uses the same dataset. However, each review here is represented by a bag-of-words of 200 most common words occuring in it.


