# data-sourcing-challenge
Module 6 Challenge Assignment

# Solution 
1) Access NY Times API and get movie titles using the criteria provided
2) Get Movie details from the TMDB API
3) Merge NT Times Data with the TMDb data, clean, and send the output to a CSV

# Source code
1) retrieve_movie_data.ipynb

# API keys
API keys are generated by each individual and stored locally for accessing them throug the jupyter-notebook
1) NYT Times
   url = "https://api.nytimes.com/svc/search/v2/articlesearch.json?" is used for searching articles / reviews using the filter query and other parameters.
2) TMDB DB:
   "https://api.themoviedb.org/3/search/movie?query=" is used for get the movie_id using a search text.
   "https://api.themoviedb.org/3/movie/" is used for getting movie_details using movie_id

# Output
1) movies.csv 

