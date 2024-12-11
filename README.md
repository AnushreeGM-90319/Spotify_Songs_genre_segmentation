# Spotify_Songs_genre_segmentation


Dataset Information
• Source: Provided CSV file containing Spotify song data.
• Dataset Features:
o Audio Features: Danceability, Energy, Tempo, Valence, Acousticness, 
Instrumentalness, Loudness, etc.
o Metadata: Playlist Genre, Playlist Name.
• Size: Dataset size varies depending on the source (assumed multiple rows and 
attributes).
• Target: No explicit target variable (unsupervised learning).



Data Preprocessing:
o Missing Value Handling: Handled missing data using forward-fill or imputation 
techniques.
o Feature Scaling: Standardized numerical features for uniform clustering.
o Feature Encoding: Encoded categorical variables like playlist genres or names.
2. Exploratory Data Analysis (EDA):
o Correlation Matrix:
▪ Analyzed relationships among audio features.
▪ Strong correlations observed, e.g., Danceability and Energy.
o Visualizations:
▪ Histograms and box plots for feature distributions.
▪ Pair plots to explore relationships between features.
o Key Insights:
▪ Higher danceability and energy often align with upbeat genres.
▪ Acousticness and instrumentalness are prominent in classical or 
ambient genres.
3. Clustering:
o Clustering Algorithm: K-Means Clustering.
o Optimal Clusters:
▪ Determined using the Elbow Method (optimal clusters = 5).
o Cluster Visualization:
▪ Reduced dimensionality with PCA for 2D visualization.
▪ Plotted clusters to show groupings of songs with similar features.
4. Model Results:
o Songs were grouped into five distinct clusters based on audio features.
o Cluster Characteristics:
▪ Cluster 1: High energy, low valence (intense tracks).
▪ Cluster 2: High acousticness and instrumentalness (ambient or 
classical tracks).
▪ Cluster 3: Balanced features (general pop songs).
▪ Cluster 4: High tempo and danceability (party tracks).
▪ Cluster 5: Low energy and tempo (calm or chill tracks).
5. Final Output:
o Labeled dataset with clusters assigned to each song.
o Exported cluster information for integration into a recommendation engine.






Key Findings:
o Songs grouped effectively into clusters based on audio features.
o Each cluster represents a unique genre or mood.
o Playlist genres align well with audio feature clusters.
• Visualization Highlights:
o PCA Scatter Plot: Showed clear separation of clusters.
o Elbow Plot: Helped identify the optimal number of clusters.
