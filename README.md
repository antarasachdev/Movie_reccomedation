# Movie_reccomedation
# 🎬 Content-Based Movie Recommender System with Sentiment Analysis using AJAX

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![Technique](https://img.shields.io/badge/NLP-Sentiment%20Analysis-yellow)

A web-based movie recommender system that recommends similar movies based on content and analyzes user sentiment on reviews. The system combines content-based filtering and natural language processing, providing an interactive and intelligent user experience using AJAX for real-time updates.

---

## 📌 Overview

This project allows users to:
- Search and view movie details (title, genre, rating, poster, etc.).
- Get recommendations for similar movies based on metadata.
- View real-time sentiment analysis of user reviews.

The application fetches movie metadata using an API, scrapes user reviews from the web, and performs sentiment analysis using NLP techniques. AJAX is used for a seamless user experience without reloading the page.

---

## ⚙️ How It Works

### 🎥 Movie Metadata Retrieval
- Retrieves movie information using an external API with a movie ID.
- Displays poster, cast, runtime, ratings, and genres on the UI.

### 🧠 Recommendation Engine
- Uses content-based filtering (genre, keywords, director, etc.).
- Vectorizes textual features using CountVectorizer or TfidfVectorizer.
- Calculates cosine similarity to find and rank similar movies.

### 🔍 Sentiment Analysis
- Scrapes user reviews from the web using BeautifulSoup.
- Cleans and processes the reviews using NLP.
- Classifies each review as Positive or Negative using TextBlob or VADER.
- Displays sentiment results alongside the recommended movies.

### ⚡ Real-Time Interaction
- AJAX enables fetching recommendations and sentiment analysis without page reloads.
- Smooth UI experience with asynchronous data flow.

---

## 🧠 Cosine Similarity

Cosine similarity is used to compare movies based on their vectorized features. It measures the cosine of the angle between two movie vectors in a multi-dimensional space. A score closer to 1 indicates high similarity.

