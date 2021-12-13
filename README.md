# Machine_Learning_Spotify_Project
This repo contains the final machine learning project documents 

## Title: P34 Build a classification model and recommendation model using Spotify data
- Team: Neha Sharma, Muhammad Awais Ali, Farooq Ayoub Dar
- Project type: self-proposed
- Description: Scrape Spotify data (own data  using spotipy API), build classification model using supervised learning approach to see whether a user will like a song or not. 
Merge all users’ data for recommendation models. Start from the baseline model (KNN with different distance matrix like manhattan distance) and modify these recommendations using 
“content based filtering” or “collaborative filtering” depending on the data availability for users and content.  
Overall goal for the recommendation model is to induce a diversity of recommended items to users as much as possible.  
For classification tasks we can start from the baseline model(Logistic regression) and evaluate performance using other models like random forest, catboost etc. 
Performance matrix depends on the domain of classification, we can calculate precision/ recall/ F1score. We can use PCA for dimensionality reduction. 
Grid search/random search can be used for hyperparameter tuning for our models. There could be a possibility for a feature engineering task as the data for classification will contain song features like danceability, acounticness, loudness etc. 
We can use the Lasso model for selecting the best features for our model.
_Note: users need to have playlists on spotify or need to create different playlists for liked songs or disliked songs._
