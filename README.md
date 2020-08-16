# Recommender
Recommender is a movie recommendation system which makes use of **memory based & model based collaborative filtering** to recommend the movies 
which have a higher correlation with the movie which one want's to compare.

# Dependencies explained
Two most ubiquitous types of recommender systems are **Content-Based Filtering** and **Collaborative Filtering (CF)**. 


**Collaborative filtering** produces recommendations based on the knowledge of users’ attitude to items, that is it uses the “wisdom of the crowd” to recommend items. 
* The algorithm has a very interesting property of being able to do feature learning on its own, which means that it can start to learn for itself what features to use.
* CF can be divided into Memory-Based Collaborative Filtering and Model-Based Collaborative filtering.

**Content-based recommender systems** focus on the attributes of the items and give you recommendations based on the similarity between them.

# Data
We will use **MovieLens dataset**, which is one of the most common datasets used when implementing and testing recommender engines. 
It contains **100k movie ratings** from **943 users** and a selection of **1682 movies.** 


To download the dataset : [Click Here](http://files.grouplens.org/datasets/movielens/ml-100k.zip)

# Objective
Predict how a user will rate a movie, given ratings on other movies and from other users.
