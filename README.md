# CMSC320-Final-Project
Tejasa Yaddula, Aastha Gautam

# Dataset: Spotify’s most streamed songs; consists of musical attributes of songs with percentages, as well as streaming metrics, and track identifying information.
# Reference: Spotify most streamed songs. (2024, September 7). Kaggle. https://www.kaggle.com/datasets/abdulszz/spotify-most-streamed-songs

This project explores whether whether characteristics of a song correlation to popularity of that song. In this case, we measured popularity by the number of streams. We found correlations between song characteristics and streaming metrics and then we attempted to predict popularity of a song with different chracteristics using a training and testing set. 

# Insights and Conclusion
From our predictive model, we were able to identify playlist inclusion as the central predictor of increasing streams for a song. After that, release year and BPM predict song popularity pretty well. Spotify and other streaming platforms can utilize this to understand how to increase song popularity and in turn increase user engagement.

A limitation of this project include a small training and testing set. In order to show the success of the model, it could be tested with updated most streamed songs, and improved through multiple trials.

# 1. Does an uninformed reader feel informed about the topic?
Yes, an uninformed reader would likely feel informed after reading through the project. The structure is clear and logical, providing an introductory background on the dataset and how it is used to understand song popularity. The reader is guided through various analyses such as:

# Dataset Parsing & Summary Statistics: 

The project explains how the dataset is parsed and processed, converting important columns into numeric data and providing basic statistics to set the context.

# Visualizations: 

View Visualizations in notebook. Graphs such as the distribution of release years, scatter plots for features like danceability vs. streams, and heatmaps for correlations provide a visual understanding of the relationships between musical features and popularity.

# Correlation and Insights: 

The project explores correlations between different features (danceability, energy, key, BPM, etc.) and streams. It also discusses genre analysis, artist collaboration impact, and seasonality trends—helping the reader understand key factors influencing a song's success on Spotify.

Random Forest Model: For readers interested in a deeper, data-driven understanding, the project delves into predictive modeling. Using Random Forest to predict streams based on various features provides a more advanced, quantitative perspective.

# 2. Would a reader who already knew about the topic feel like they learned more about it?
Yes, even a reader with prior knowledge about Spotify and its music trends would find valuable insights in this analysis. While they may already be familiar with general concepts like song popularity, danceability, BPM, and playlists, the project takes a deeper dive into:

# Correlation Insights: 
By examining how specific features like danceability, BPM, and acousticness correlate with streams, the project uncovers relationships that may not be immediately obvious. For example, the slight negative correlation between danceability and popularity could offer a fresh perspective for someone already familiar with Spotify trends.

# Artist Collaboration Impact: 
The analysis on whether collaborations lead to higher streams provides an interesting nuance that even informed readers might not have considered, exploring this factor quantitatively.

# Playlist Influence: 
The correlation between playlist inclusion (on Deezer, Shazam, Spotify, etc.) and streams offers a deeper understanding of the role of playlists in driving popularity, which is a critical aspect of modern music discovery.

# Predictive Modeling: 
The use of Random Forest modeling adds an advanced analytical layer, showing how features contribute to stream predictions. For data science enthusiasts, the inclusion of feature importance rankings and model evaluation (MSE, R²) provides a concrete understanding of which features are most influential in predicting popularity.
