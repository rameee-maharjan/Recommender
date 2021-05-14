# Movie Recommendation and rating prediction using Netflix dataset

Dataset specification: Netflix dataset
ratings.txt has each row in the form of movieId, userId, rating.

Platform/Programming Language: Jupyter Notebook, Python

Approach:
For this project, we have calculated movie-to-movie similarity using correlation coefficient.
A movieId and a userId is randomly chosen for the rating prediction for which we used k=15 to find most similar 15 movies that user have rated.
User may have rated less than 15 movies in which case we have used all of them and calculated average of the ratings for those movies.

To recommend a movie to a userId, we have listed all the movies that have been highly rated by the user (at least 3.0).
We found the most similar movies to these highly rated movies. The top 10 movies are then recommended to the user.
  
