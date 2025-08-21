# spotify-song-recommender
Spotify-Style Recommender 🎵
A machine learning–based music recommendation system inspired by Spotify’s recommendation engine. The project uses collaborative filtering, content-based filtering, and deep learning techniques to suggest songs based on user preferences, listening history, and audio features.

# Goal:
To build an intelligent music recommendation system that analyzes user preferences, listening behavior, and song features to deliver personalized song suggestions, enhance user experience, and enable automatic playlist generation similar to platforms like Spotify.

# What I Did in the Project:
Data Collection & Preprocessing: Gathered and cleaned song datasets (audio features, metadata, user listening history) from sources like Kaggle/Spotify API.
Exploratory Data Analysis (EDA): Analyzed user behavior and audio features (tempo, energy, valence, etc.) to understand patterns.
Model Development:
Implemented Content-Based Filtering to recommend songs based on audio similarity.
Applied Collaborative Filtering (Matrix Factorization/Surprise/Neural CF) for user–item interactions.
Built a Hybrid Model to combine both approaches for better accuracy.
Evaluation: Measured model performance using metrics like precision, recall, F1-score, RMSE.
Deployment: Created a simple Streamlit/Flask dashboard to generate personalized song recommendations and playlists.
Documentation: Added visualizations, clear explanations, and results for reproducibility.

# Model Used:
1. K-Means Clustering
* Most common choice.
* Groups songs based on audio features (tempo, energy, danceability, etc.).
* New songs are recommended from the same cluster as the user’s liked songs.
2. Hierarchical Clustering (Agglomerative/Divisive)
* Builds a hierarchy of clusters to group similar songs.
* Useful for small-to-medium datasets and when visualizing song similarity.

# Libraries Needed
* Numpy
* Pandas
* matplotlib
* seaborn
* SKlearn
* PCA (Principal Component Analysis): sklearn.decomposition.PCA
