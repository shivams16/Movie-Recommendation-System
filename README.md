# Movie-Recommendation-System
This project is based on machine learning with python which works on predefined datasets and
simply recommends users new movies based on ratings and its personal experience. In this project
we implement python libraries and uses bootstrapped aggregation, and correlations to reach our
goal.

Recommender systems have become ubiquitous in our lives. Yet, currently, they are far from optimal.
In this project, we attempt to understand the different kinds of recommendation systems and compare
their performance on the MovieLens dataset. We attempt to build a scalable model to perform this
analysis. We start by preparing and comparing the various models on a smaller dataset of 100,000
ratings. Then, we try to scale the algorithm so that it is able to handle 20 million ratings by using
Apache Spark. We find that for the smaller dataset, using user-based collaborative filtering results in
the lowest Mean Squared Error on our dataset.
