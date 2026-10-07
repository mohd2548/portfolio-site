# 🎬 Movie Recommender System

An end-to-end Machine Learning + Flask web application that recommends movies using **content-based filtering** on the TMDB dataset.  
The system builds a personalization engine that analyzes movie metadata (genres, keywords, cast, crew, and overview) to suggest 5 highly relevant movies with rich details.

---

## 📌 Project Overview
This project processes text metadata from the **TMDB 5000 Movies & Credits datasets**.  
By applying **Text Preprocessing (Stemming)** and **Vectorization (CountVectorizer)**, the model computes similarity distances between movies.  
A user-friendly **Flask web interface** allows users to select a movie and instantly receive recommendations.

---

## 🛠️ Tools & Technologies
- **Python** — Core programming language  
- **Pandas, NumPy** — Data manipulation & cleaning  
- **Jupyter Notebook** — Exploratory Data Analysis (EDA)  
- **NLTK (PorterStemmer)** — Text preprocessing  
- **Scikit-Learn (CountVectorizer, cosine_similarity)** — NLP + ML pipeline  
- **Pickle** — Model serialization  
- **Flask** — Web application backend  

---

## 📂 Project Structure
