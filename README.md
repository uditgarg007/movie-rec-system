# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built with **Python and Streamlit** that recommends similar movies based on the user's selection.

The system analyzes movie metadata and computes similarity between movies using **machine learning techniques** to generate personalized recommendations.

---

## 🚀 Live Demo

🔗 **Try the app here:**  
https://movie-rec-system-udit.streamlit.app/

---

## 📌 Features

- Select a movie from the dropdown list
- Get **Top 5 similar movie recommendations**
- Displays **movie posters**
- Fast recommendation system using **precomputed similarity**
- Interactive UI built using **Streamlit**

---

## 🧠 How the Recommendation System Works

This project uses **Content-Based Filtering**.

### Steps

1. Movie metadata (genres, keywords, cast, crew) is processed.
2. Text features are combined into a single representation.
3. A **vectorization technique** is applied to convert text into numerical features.
4. **Cosine similarity** is computed between all movies.
5. When a user selects a movie, the system recommends the **most similar movies**.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Streamlit**
- **Requests**
- **TMDB API**

---

## 📂 Project Structure
