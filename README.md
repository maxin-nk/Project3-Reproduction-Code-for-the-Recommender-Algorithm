# Project-3-Reproduction-Code-for-the-Recommender-Algorithm

# ALS
A matrix decomposition algorithm that uses alternating training to obtain a set of user and item embeddings that approximates the original user-item matrix by means of an embedding dot product.

# BPR
It provides an optimization function. Instead of predicting the ratings of specific user and item pairs, it ranks the items consumed by users according to their preferences.

# KNN
It is a basic memory-based recommendation method based on calculating item-item similarity. In this method, an item is recommended to a user if it is similar to an item previously selected by the user. In CF systems, items selected by the same group of users are considered more similar than items from non-overlapping groups of users.

# POP
A simple, non-personalized baseline algorithm that recommends the same list of Top-n item recommendations to each user in terms of item popularity.

# SLIM
It is a linear model designed to compute Top-n recommendations by factorizing the item-item co-occurrence matrix under non-negativity L1 and L2 constraints. The learned item coefficients are used to sparsely aggregate past user interactions and predict the items recommended by users.

# VAE
It is a variational autoencoder architecture that first projects sparse user interaction vectors onto a potential distribution space, which is later used to generate probability distributions for all items.MultiVAE employs polynomial likelihood and different regularization procedures involving linear annealing.
