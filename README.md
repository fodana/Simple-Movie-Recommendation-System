A simple movie recommendation system built using python, pandas, scikit-learn, and NLP techniques. The system suggests movies based on the content of the movie descriptions, genres, keywords, cast, and crew. 

Key features include:
Data Preprocessing: Merges movie metadata and credits, cleans and formats data, extracts relevant columns, and handles missing values.
Text Processing: Converts text data (genres, keywords, cast, crew) into a unified format using techniques like tokenization, stemming, and removal of unnecessary characters.
Feature Extraction: Utilizes Count Vectorizer to transform the textual data into numerical vectors based on word frequency.
Cosine Similarity: Measures the similarity between movies based on the vectorized features.
Recommendation Function: The recommend() function outputs the top 5 movies most similar to a given movie title based on cosine similarity.
