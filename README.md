Tweets Sentiment Analysis
Sentiment analysis on Twitter data has attracted much attention recently. This program is a simple implementation of a sentiment classifier for a tweet.

Based on the sentiwordnet corpus, the classifier can distinguish if a tweet is Positive, Negative, or Objective.

Usage
To see answers to the TP : python tp.py
To see the results of the classification using the first version of the algorithm : python tpv1.py
To see the results of the classification using the second version of the algorithm : python tpv2.py
To see the results of the classification using the third version of the algorithm : python tpv3.py
Requirements
You need the following libs :

sklearn
nltk
numpy

2 Pre Processing
User-generated content on the web is seldom present in a form usable for learning. It becomes important to normalize the text by applying a series of pre-processing steps. We have applied an extensive set of pre-processing steps to decrease the size of the feature set to make it suitable for learning algorithms. Figure 2 illustrates various features seen in micro-blogging. Table 3 illustrates the frequency of these features per tweet, cut by datasets. We also give a brief description of pre-processing steps taken.

Figure
