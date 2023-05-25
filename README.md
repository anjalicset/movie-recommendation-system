# movie-recommendation-system
Movie recommendation system based on the overview, genre, keywords, cast, and crew of the movie
The code is for a movie recommendation system that loads data from two CSV files, tmdb_5000_credits.csv and tmdb_5000_movies.csv, merges them, preprocesses the data, creates a new column 'tags' that includes all the keywords based on overview, genre, keywords, cast, and crew for each movie, vectorizes the tags column, and uses cosine similarity to find similar movies.

The data is sourced from Kaggle(https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) having data from, the TMDb (The Movie Database) , which is a popular database for movie and TV show information.

The code is written in Python using libraries such as pandas, numpy, matplotlib, and scikit-learn. It defines functions to preprocess the data, create feature vectors, and recommend movies. It also uses the PorterStemmer algorithm to stem the text data and reduce the number of unique words. Lastly, it saves the preprocessed data and similarity matrix to pickle files for future use.
