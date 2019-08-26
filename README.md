# twitterCluster
Unsupervised learning cluster analysis of tweets that mention airlines from the USA.

Functionality: Clustering tweets containing information on how users spoke about airlines from the USA in February 2015. This template can be used with any unlabelled text data. This same path could be followed to cluster any dataset with many rows containing text. The number of clusters need to be chosen.

Steps: 
<p>1.- Counting most frequent words, bigrams and trigrams.</p>
2.- Creating a stemmed corpus with nltk.
3.- Using Kmeans in order to get clusters.
4.- Analyzing most representative tweet from each cluster.

Dataset: https://www.kaggle.com/crowdflower/twitter-airline-sentiment

