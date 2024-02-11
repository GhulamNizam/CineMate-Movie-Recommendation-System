# CineMate-Movie-Recommendation-System
This project is inspired by the "Movie Recommender System" tutorial on the "xcampus" YouTube channel. While the core concepts are based on the tutorial, 
this repository includes additional modifications and enhancements for personal learning and exploration.

Welcome to CineMate, a movie recommendation system developed using CountVectorizer and cosine similarity. This system preprocesses raw data, including using ast.literal_eval to handle list features, extracting only relevant information from dictionaries, and creating a new feature called 'tags' to facilitate corpus creation and prediction. After calculating similarity, it keeps only the top 5 recommendations with the highest similarity scores. Additionally, this project includes deployment on Streamlit for easy access and interaction.

## Overview

CineMate aims to provide personalized movie recommendations based on user preferences and similarities between movies. By leveraging natural language processing techniques and cosine similarity, it suggests movies that are most similar to those the user enjoys.

## Features

- **Preprocessing:** Handles raw data preprocessing, including parsing list features and extracting relevant information.
- **Cosine Similarity:** Calculates similarity between movies using CountVectorizer and cosine similarity.
- **Top Recommendations:** Recommends the top 5 movies with the highest similarity scores.
- **Streamlit Deployment:** Deploys the recommendation system on Streamlit for user-friendly interaction.

<!--##! Getting Started

1. Clone or download this repository to your local machine.

2. Ensure you have the necessary dependencies installed. You can install them using pip:-->


