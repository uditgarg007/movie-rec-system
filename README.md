# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built with **Python and Streamlit** that recommends similar movies based on the user's selection.

The system analyzes movie metadata and computes similarity between movies using **machine learning techniques** to generate recommendations.

---

## 🚀 Live Demo

🔗 https://movie-rec-system-udit.streamlit.app/

---

## 📌 Features

- Select a movie from the dropdown menu
- Get **Top 5 similar movie recommendations**
- Displays **movie posters**
- Interactive UI built using **Streamlit**
- Fast recommendation system using **precomputed similarity matrix**

---

## 🧠 How the Recommendation System Works

This project uses **Content-Based Filtering**.

### Steps

1. Movie metadata such as **genres, keywords, cast, and crew** are processed.
2. The relevant features are combined into a single representation.
3. Text data is converted into vectors using **vectorization techniques**.
4. **Cosine similarity** is computed between all movies.
5. When a movie is selected, the system recommends the **most similar movies**.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Requests
- TMDB API

---

## 📂 Project Structure
movie-rec-system/
│
├── app.py
├── movie_recommendation.ipynb
├── movie_dict.pkl
├── similarity.pkl
├── requirements.txt
└── README.md
