# Movie-Recommendation-System
A movie recommendation system is a project that uses data analysis and machine learning techniques to suggest movies to users based on their preferences, ratings, and feedback. The goal of this project is to provide personalized and relevant recommendations that enhance the user experience. A movie recommendation system based on cosine similarity is a way of finding movies that are similar to a given movie based on their features. Cosine similarity is a measure of how close two vectors are in terms of their angle. The higher the cosine similarity, the more similar the movies are. For example, if we have a feature vector that represents the genre, cast, director, and rating of a movie, we can calculate the cosine similarity between two movies by taking the dot product of their feature vectors and dividing it by the product of their magnitudes. This will give us a value between -1 and 1, where 1 means the movies are identical, 0 means they are orthogonal, and -1 means they are opposite. A movie recommendation system based on cosine similarity can use this value to rank the movies in order of similarity to the given movie and suggest the top ones to the user.

# Movie Recommendation System - Cosine Similarity

- The goal of this project is to build a movie recommendation system using machine learning techniques.
- The main idea is to measure the similarity between movies based on their descriptions, genres, cast, directors, and keywords.
- The similarity metric used is cosine similarity, which calculates the angle between two vectors of features.
  
- The steps involved are:
- Preprocessing the data by cleaning the text, removing stopwords, and applying stemming or lemmatization.
- Extracting features from the text using TfidfVectorizer, which assigns weights to words based on their frequency and importance.
- Computing the cosine similarity matrix for all movies using the feature vectors.
- Taking a movie title as input from the user and finding the most similar movies based on the cosine similarity scores.
- Displaying the recommended movies to the user along with their details.
- The libraries used are difflib, which helps in matching the input movie title with the existing titles, and pandas, numpy, and sklearn, which provide various tools for data manipulation and machine learning.
