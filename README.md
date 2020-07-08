# Introduction

We judge people attractiveness on the information provided by the online reviewers. We extracted the twitter data using Twitter API. TO meet the goals, we developed and tested several machine learning algorithms. The data extracted from the twitter are the retweets of the trump by unknown persons. The information from the data like single word textual explanation judges the trump attractiveness by how many people like him or hate him. We extracted the feature set which is bag of words and performed machine learning algorithms. The accuracy was too low after using the bag of words for methods, so tried using the algorithms without using the libraries and compared with them with sklearn library used functions which results naive Bayes as the best algorithms for this
classification.

# Framework

We will be using Python as a programming language for implementation of our project. Jupyter Notebook Python 3.7.4 will be used as editor. Tweepy python library for Twitter API will be used to fetch tweets for the personality.
The process consist of following steps :

•Data Collection

•Data Cleaning which includes removing hashtags,links, stop words, stemming, lemmatization.

•Feature Extraction which consist of Count vectorizer, bag of words, TD-IDF.

•Machine Learning Algorithms like Naïve Bayes, SVM, Random Forest and Logistic Regression.
