# Movies-Recommendation-System

Movifie is a content-based movies recommendation system built using cosine similarity. The front end is made using the streamlit API and integrated with the help of tmdb API to get back the value of recommendations tags. 
Moviefie takes input of a movie name and suggest 5 closest recommendations, which is picked out by doing text vectorization on the tags category made up from the datasets value of (cast, crew, genres), and the NLP technique of Bag of words.
The app is deployed on heroku.

Working Project Link: https://moviefie.herokuapp.com/ \n
DataSet Link: https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
