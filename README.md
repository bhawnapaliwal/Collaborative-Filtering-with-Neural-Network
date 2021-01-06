# Collaborative-Filtering-with-Neural-Network

The repository consists of the implementation of neural collaborative filtering based on the course term paper.
 
## Abstract of the implemented approach discussion

The aim is to build recommendation systems for explicit feedback systems where the task
is to recommend items to users based on a rating matrix which is a matrix where cell (i,j) corresponds
to the rating user ’i’ gave to item ’j’. Based on these ratings, the system tries to predict unfilled
ratings in the matrix i.e. predicts intelligently what rating value an item might get by a user. The
traditional collaborative filtering technique for recommender systems depends upon the similarity
values between two given user or item vectors in the rating matrix. But the technique in general
suffers from some major problems such as sparseness of user profiles and scalability. [1] Deep neural
networks have achieved success in various fields such as image classification, segmentation, speech
recognition and and many other domains. The idea is to replace the inner product in the matrix
factorization with a deep neural network. [2] The technique of neural collaborative filtering [2] has been
used in systems based on implicit feedback which classifies a given item by all the users as either
might be interested in or not interested in, the task in explicit feedback systems is to have techniques
for getting the the exact ratings from 1 to 5 that user might give to an item. We implement two different
approaches to use Neural Networks with collaborative filtering (implemented in NeuMF.ipynb) and matrix factorization and concatenation (implemented in embed_concat.ipynb) where we
concatenate user and item embeddings and then develop a model over them.

## Medium Article

https://medium.com/@bhawna7374/movie-recommendation-system-with-neural-networks-and-collaborative-filtering-explicit-feedback-d2afaafef350
