# 🎬 Movie & Web Series Recommendation System

A full-stack **content-based recommendation system** built using Natural Language Processing (NLP). The system suggests similar movies and web series based on textual similarity of metadata such as description, genres, keywords, and other features.

It uses **TF-IDF vectorization** to convert text into numerical form and **cosine similarity** to compute relationships between content. The backend is built with **FastAPI**, and the frontend is developed using **Streamlit** (running on a local server).

---

## 🚀 Features

* 🎯 Content-based movie & web series recommendations
* 🧠 NLP-based feature extraction using TF-IDF
* 📊 Cosine similarity for ranking similar content
* ⚡ FastAPI backend for efficient API handling
* 🖥️ Interactive Streamlit web interface
* 📁 Works with Kaggle movie dataset
* 🔍 Fast and responsive recommendation engine

---

## 🧠 How It Works

1. Movie and web series metadata (overview, genres, keywords, etc.) is collected from the dataset
2. Text data is preprocessed and cleaned using NLP techniques
3. **TF-IDF Vectorization** converts text into numerical feature vectors
4. **Cosine Similarity** is computed between all movies
5. When a user inputs a movie name, the system finds the most similar titles based on similarity scores
6. Results are displayed in the Streamlit interface

---

## 🛠️ Tech Stack

* Python 3
* Pandas, NumPy
* Scikit-learn
* NLP (TF-IDF Vectorizer)
* FastAPI (Backend API)
* Streamlit (Frontend UI)

---

## 📂 Dataset

* Kaggle dataset containing movies and web series metadata
* Includes fields like:

  * Title
  * Genre
  * Overview
  * Keywords
  * Cast (if available)

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository

```bash id="c9f1k2"
git clone https://github.com/your-username/Movie-Recommendation-Project.git
cd Movie-Recommendation-Project
```

---

### 2️⃣ Install dependencies

```bash id="x8q2v9"
pip install -r requirements.txt
```

---

### 3️⃣ Run FastAPI backend

```bash id="f7d2m1"
uvicorn app:app --reload
```

---

### 4️⃣ Run Streamlit frontend

```bash id="s2k8p4"
streamlit run streamlit_app.py
```

---

## 🌐 Usage

* Open Streamlit in browser
* Enter a movie or web series name
* System sends request to FastAPI backend
* Backend computes similarity and returns top recommendations
* Results are displayed instantly

---

## ⚠️ Limitations

* No collaborative filtering (only content-based)
* Not deployed online yet (local server only)
* Recommendation quality depends on dataset richness

---

## 📈 Future Improvements

* 🌍 Deploy backend (Render / Railway / AWS)
* ☁️ Deploy frontend (Streamlit Cloud)
* 👥 Add collaborative filtering (user-based recommendations)
* 🤖 Improve NLP using embeddings (Word2Vec / BERT)
* 🔎 Add search autocomplete feature
* 📱 Make mobile-friendly UI

---

## 👨‍💻 Author

**Nilkontha Das**

---

## 📌 Project Type

* Machine Learning (NLP)
* Full-Stack Application
* Recommendation System

---

## ⭐ Note

This project is built for learning and portfolio purposes to demonstrate NLP-based recommendation systems and full-stack ML application development.
