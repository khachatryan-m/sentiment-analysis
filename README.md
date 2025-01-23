# Sentiment Analysis On Movie Reviews using Naive Bayes Approach
The primary goal of the project is to identify whether a person liked the movie based on the review they gave. 

# Dataset
The movie dataset used for this analysis is from Imdb. It is publicly available, can be downloaded from here (https://ai.stanford.edu/~amaas/data/sentiment/) or from this repository. Each review in the dataset is labeled as positive (1) or negative (0). 
The data is split with a 80:20 ratio for training and testing sets, i.e. 40K items for training and 10K items - for testing.

# Feature engineering and modelling
For feature extraction, we used BoW (Bag of Words) technique. BoW works by representing text data as a multiset of words, disregarding grammar and word order but retaining information about word frequency. It operates on the principle of tokenization, 
wherein each document's text is broken down into individual words or tokens. These tokens are then represented as a sparse matrix, where rows correspond to documents and columns represent unique words found in the corpus.

For modelling, traditional Naive bayes algorithm is used with its likelihood function, prior and posterior.
![Screenshot (42)](https://github.com/user-attachments/assets/7c650fb9-9023-436c-ab73-5fd153c6b426)

The model has an average accuracy of 83% and a precision of 84.5%.



