This is an example of Twitter Sentiment Analysis using TextBlob.

TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

More on TextBlob : http://textblob.readthedocs.org

Get it now:
$ pip install -U textblob
$ python -m textblob.download_corpora


This example shows the use of TextBlobl's in-built sentiment analyzer - Naive Bayes Analyzer.
We Train it with a few sample tweets and then test it using some test tweets and finally compare the results.


To execute tweet_classify.py at the terminal:
$ ./tweet_classify.py
