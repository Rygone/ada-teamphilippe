---
layout: home
title: Opinions in news and success of Meta (or Mark Zuckerberg)
subtitle: Data Story
---

---
# Skeleton
# Abstract & introduction
An introduction about project and why it could be useful.



# Sentiment analysis 
## Global result
Explain global result about sentiment analysis on the quotes concerning Mark Zuckerberg.
## Clustering
Decompose the analysis into smaller groups.
### Investigate clusters
Result of the custom K medioids algorithm and small investigation of the clusters.
## Regression analysis
### Stock price
Explain how we will quantify the success of the companies.
### Regression analysis on specific attributes
Explain how we did regression analysis and present the results when splitting on different attribute values.
### regression analysis on the clustering
Show and comment the regression analysis result on the group extracted via clustering.

# Conclusion
---
# Introduction
## Abstract
With the world getting more and more connected, in particular the domain of news and journalism,
we get access to opinions of huge amount of people. These opinions can express negative, positive or
simply neutral sentiments about a subject or person. Public personalities like Mark Zuckerberg are
particularly exposed to criticism, being positive or negative. But do these online opinions really affect
his success ? Opinions of specific groups of people may indicate a rise or a fall
in his career.


In this article, we will identify the polarity of opinions in the news and try to identify different types
of authors. The study of the polarity of the opinions of each of these groups will then allow us to
potentially identify specific types of people that are a good indicators of the success of Mark Zuckerberg. 

## Data and Methods
We use a subset of the [QuoteBank dataset](https://dlab.epfl.ch/people/west/pub/Vaucher-Spitz-Catasta-West_WSDM-21.pdf)
which contains quotes made in English-speaking news articles published between 2015 and 2020. To measure the success
of Mark Zuckerberg, we use the stock price of his company Meta on the [Nasdaq Stock Market](https://www.nasdaq.com/market-activity/stocks/fb/historical).


