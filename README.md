# Tales-from-the-Crypto
Natural Language Processing

This document compares Bitcoin to Ethereum using Natural Language Processing to determine the sentiment and named entity recognition from news articles.

## Sentiment Analysis

Based on the review of multiple news articles, Ethereum has higher postive sentiment.

* Ethereum has a higher positive mean 0.072 versus bitcoin 0.046

* Bitcoin has the highest negative score with a max negative score 0.277000	 versus Ethereum 0.177000

* Ethereum has the highest positive score with a max positive score 0.226000 versus Bitcoin 0.149000

The negative view of Bitcoin maybe because it is more well known, therefore more people know the negative aspects of Bitcoin. I'd never heard of Ethereum until this year.

## Natural Language Processing
### Word Clouds

I expand the default stopwords list

![btc-word-cloud.png](Images/Bitcoin_WordCloud.png)

![eth-word-cloud.png](Images/Ethereum_WordCloud.png)

## Named Entity Recognition

In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.
