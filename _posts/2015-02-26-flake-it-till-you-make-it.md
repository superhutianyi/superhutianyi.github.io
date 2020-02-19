---
layout: post
title: News Sentiment on Stock Market Prediction
subtitle: This is about news sentiment on stock market prediction.
bigimg: /img/path.jpg
tags: [news sentiment, stock prediction, sentiment analysis, machine learning, naive bayes, random forest]
---

The research question in this paper is that how effective is the prediction of stock price fluctuations using textual worldwide news articles? 

The main methodology is like following: The first step is to do the text cleaning, including converting into a lower case; dropping the noisy words; removing numbers, white spaces, tabs, punctuation characters, stop words etc.; tokenize the text document into words; doing stemming or lemmatization process. The second step is to do the Polarity Detection Algorithm, where I used VADER/LM dictionary in this step. I also did TF-IDF Analysis to figure out which word is characteristic for one text document within a collection of documents. Finally we did a Stock Prediction using Machine Learning Models, such as Naive Bayes/Random Forest/SVM, and got an accuracy over 80%.

There still exists some limitations in this paper. For example, high fluctuations in prices may result in the uncertainty of the dataset. Similarly, we have limitation in time series algorithms and limitation in stock selection as well.

If you are interested about this page, please check out my github page [here](https://github.com/superhutianyi/newssentiment) I have sufficient datasets and well-done Python code there.
