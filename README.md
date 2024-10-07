# Predicting Song Popularity Using Spotify API
## Introduction
In today's music industry, predicting a song's popularity is crucial for artists, producers, and marketers. By analyzing audio features and metadata from Spotify, this project aims to develop a machine learning model to categorize songs based on their potential popularity, helping stakeholders optimize content production, promotional strategies, and playlist curation.

## Problem Statement
The project seeks to develop a classification model to predict the popularity category of Spotify songs based on audio features and metadata. This model will provide insights that assist artists, producers, and marketers in making data-driven decisions to enhance their content and marketing strategies.

## Project Overview
This project utilizes the Spotify API to extract audio features and metadata such as danceability, energy, loudness, valence, and tempo. Multiple models were tested, with the Random Forest Classifier selected as the best-performing model for predicting song popularity.

- Best Model: RandomForestClassifier (random_state=42)
- Accuracy: 72.5%
- Precision: 72.9%
- F1 Score: 72.0%
- Cohen Kappa: 0.577
  
The model is deployed using Gradio to allow real-time song popularity predictions based on the provided features.

## Models and Techniques
- Random Forest Classifier: Best model based on accuracy and Cohen Kappa.
- Logistic Regression, Decision Tree, XGBoost, and AdaBoost: Other models were evaluated.
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, and Cohen Kappa.
- Feature Engineering: Audio features and metadata were used for model training.
## Files Included
- Song Popularity Prediction_ Model Building.ipynb: Contains the steps for data extraction, preprocessing, statistical analysis, feature engineering, and model development.
- Song Popularity Prediction_ Testing & Deployment.ipynb: Shows the testing of the model and its deployment using Gradio for real-time predictions.
## Conclusion
The Random Forest Classifier was selected as the best-performing model to predict song popularity, achieving 72.5% accuracy. Deployed using Gradio, this model allows real-time predictions of song popularity, providing valuable insights for the music industry to make informed decisions regarding content and marketing strategies.

