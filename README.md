# MovieLens-Dataset

The Movie Lens data is an extensive dataset of the Movies listed with genres ratings from various entities and this project aims at predicting the ratings of the movies from various features.
The following steps were followed to create a 3-Class Classification Supervised Learning problem.


1. Pre-process the data to center around movies:
   - Compute the average rating for each movie
   -  Normalize the Year of Movie Release so that 1990-later is "New", 1970s/1980s is "Medium" and anything in 1960s or before is "Old"
   - Assign genres to each movie.
   
2. Sort the movies by their average rating. Find the median of average rating. Pick top 20%, bottom 20% and middle 20% of the movies, calling them "Best", "Worst and "OK" respectively. 

3. Run a ML algorithm to show if/how a movie's Genre and/or Age determines its rating ("Best", "Worst", "OK").
