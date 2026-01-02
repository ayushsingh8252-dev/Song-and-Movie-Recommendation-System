# 📌 Project Overview

This project is an end-to-end Recommendation System that suggests songs and movies to users based on similarity patterns and user preferences.
It demonstrates core concepts of Machine Learning–based recommender systems, API deployment, and an interactive frontend.

🚀 Key Feature

Personalized song and movie recommendations

Content-based / collaborative filtering approach

Real-time recommendations via REST API

Interactive Streamlit UI for user interaction

Dockerized deployment for cross-platform execution

🧠 Recommendation Logic

Preprocessed song and movie metadata

Extracted features (genres, tags, ratings, similarity vectors)

Computed similarity scores to generate recommendations

Returned top-N recommendations in real time

🧩 Tech Stack

Language: Python

Machine Learning: Recommendation algorithms (similarity-based)

Backend: FastAPI / Flask

Frontend: Streamlit

Deployment: Docker

⚙️ User Flow

User selects a song or movie in the Streamlit UI

Request is sent to the backend recommendation API

ML model computes similarity and generates recommendations

Recommended songs or movies are displayed instantly
