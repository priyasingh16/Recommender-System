# Recommender-System
Implemented a movie recommender system in Python by computing user to user similarity based on ratings and movies in common and predicted the rating using weighted similarity between users.

DATATSET MovieLens 100K Ratings https://grouplens.org/datasets/movielens/100k/

Recommender System using Collaborative Filtering

* Implemented a Movie Recommendation System and run it on the Movie Lens Dataset (Train vs Test). 
* Measured performance on test set using RMSE
* Computed a user-user similarity based on ratings and movies in common
* Second, rating predictions on the test set following the KNN idea: 
  *   A prediction (user, movie) is the weighted average of other users' rating for the movie, weighted by user-similarity to the given user.

