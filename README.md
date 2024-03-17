# Product Recommendation System

This project aims to implement two types of recommendation systems: 
- Collaborative Filtering
- Popularity-Based Recommendation.

The dataset used is a collection of electronic product ratings provided by users from amazon. 

First, we explore and preprocess the data, ensuring its cleanliness and extracting relevant insights. Then, we implement both recommendation systems.

In the Popularity-Based recommendation system, products are recommended based on their average ratings and the count of ratings received. This approach suggests products with high average ratings and sufficient interactions.

In the Collaborative Filtering recommendation system, personalized products are recommended by using user-item interactions.
We implement two approaches in Collaborative Filtering:
1. User-Based Collaborative Filtering.
2. Model-Based Collaborative Filtering.

- User-Based Collaborative Filtering identifies similar users based on their ratings and recommends items liked by those similar users.
- Model-Based Collaborative Filtering utilizes matrix factorization techniques like Singular Value Decomposition (SVD) to predict ratings for unseen user-item pairs.



**Conclusion :**

By implementing both Collaborative Filtering and Popularity-Based recommendation systems, this project provides insights into different approaches for building recommendation systems. It demonstrates how these systems can offer personalized recommendations to users based on their preferences and interactions with items in the dataset.
