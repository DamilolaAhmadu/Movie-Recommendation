# Movie-Recommendation-System

![ML](https://img.shields.io/badge/ML-Recommendation_System-blue.svg) 

![logo](Snips/Logo.jpeg)

## Business Objectives :

All entertainment websites or online stores has million/billions of items. It become challenging for the customers to select the right one. Hence, recommender system will come into the picture and help the user to find the right item by minimizing the options.

Recommendation Systems in the world of machine learning has become very popular and are of huge advantages to  the tech giants like Netflix, Amazon and so many more to target their contents to a specific audience. These recommendation engines are so strong in their predictions that they can dynamically alter the state of what the users sees on their pages based on the user’s interaction with the apps.

The business objectives are : 
1. To create a Collaborative Filtering based Movie Recommendation Systems
2. Predicts the ratings a user would give to movies that he has not yet rated
3. Minimize the differences between predicted and actual ratings (RMSE and MAPE)

## Data Collection :

The data set has been obtained from Grouplen.

Link : https://grouplens.org/datasets/movielens/20m/

This data set (ml-20m) describes 5-star rating and free-text tagging activity from Movie Lens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This datasets was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users has rated at least 20 movies. No demographic information is included. Each users is represented by an id, and no other informations was provided.

The data are contained in the files genome-scores.csv, genome-tags.csv, links.csv, movies.csv, ratings.csv and tags.csv. 

For our objective, we would be using "ratings.csv" and "movies.csv" data files.

## Modelling :

The following modelling approaches was used in the project:

1. Loading & exploring the Movies and User ratings data
2. Creating User-Item Matrix, User-User and Item-Item similarity matrices for Movie Recommendations
3. Creating features and applying ML models to predict the ratings for unseen movies for a user

The detailed analysis and model creation can be found in the .ipynb file. 

## Results :

Some of the test images are shown below:

The results from Movie-Movie Similarity are as below:

![test](Snips/M_1.JPG)

The results from User-User Similarity are as below:

![test](Snips/M_2.JPG)

The Feature Importance for predicting ratings are below:

![test](Snips/M_3.JPG)

The results from different ML models are as follows:

![test](Snips/M_4.JPG)

The sample movie recommendations based on Collaborative Filtering is as follows:

![test](Snips/M_5.JPG)

## Conclusions :

In this project, we learned the importance of Recommendation Systems, the types of recommender system being implemented, and how matrix factorization is used to enhance a system. 

We also built a movie recommendation system that considers user-user similarity, movie-movie similarity, global average and matrix factorization. These concepts can be applied to any other user-item interactions systems.

We tried generating recommendations based on similarity matrix and Collaborative Filtering techniques.

We tried to predict the ratings for movies the user might give based on its past rating behaviours and measure the accuracy using RMSE and MAPE error metrics.

Surely, there is a huge scope of improvement and trying out different techniques and ML/DL algorithms.
