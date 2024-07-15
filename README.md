## Movie Recommendation System
This project involves developing and comparing two types of movie recommendation systems: a content-based recommendation system and a collaborative filtering recommendation system. The primary goal is to generate movie recommendations and evaluate their performance using RMSE and MAE metrics.

# Project Structure
1. Content-Based Recommendation System

Uses Tf-idf Vectorizer to analyze the textual content of movie datasets.
Applies cosine similarity to find and recommend movies similar to the ones a user likes.

2. Collaborative Filtering Recommendation System

Utilizes the Surprise library to predict user preferences based on ratings data.
Implements algorithms to generate recommendations by leveraging user-item interaction patterns.

Evaluation

Generates top 10 recommendations for each system.
Calculates RMSE and MAE metrics to compare the performance of the two systems.

link for rating.csv(datset for collaborative filtering) : https://drive.google.com/file/d/1wXGuG3EsOfnuweFbWDCcpb6rk2_7N1UQ/view?usp=sharing
