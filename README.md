# DataMinig_Practices
DataMining course and implementation of its academic exercises (Tarbiat Modares University)

## Part1 : Movie Ratings
This dataset {https://files.grouplens.org/datasets/movielens/ml-latest-small.zip} describes 5-star rating and free-text tagging activity from a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users between March 29, 1996 and September 24, 2018. This dataset was generated on September 26, 2018.The data are contained in the files links.csv, movies.csv, ratings.csv and tags.csv. All ratings are contained in the file ratings.csv. Each line of this file after the header row represents one rating of one movie by one user, and has the following format:

    userId, movieId, rating, timestamp

The lines within this file are ordered first by userId, then, within user, by movieId. Ratings are made on a 5-star scale, with half-star increments (0.5 stars - 5.0 stars). Timestamps represent seconds since midnight Coordinated Universal Time (UTC) of January 1, 1970.  

### Tasks:
  1. Write a MapReduce program that takes the input dataset and outputs the number of unique users who visited each page. Your program should output tuples of the form (movie_id, unique_users).
  2. Write a MapReduce program that takes the input dataset and outputs the top-rated movies.Your program should output tuples of the form (movie_id, average_rating), sorted in descending order by.
  3. You have to find the movies that are similar to a given movie, based on the MinHash algorithm estimate the Jaccard similarity.
  4. Find the movies that are closest to five arbitrary movie.
