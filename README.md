# 🎬 Movie Recommender System

## 📌 Overview

This project is a **Movie Recommendation System** built using Python and Machine Learning techniques.
It recommends similar movies based on user selection.

---

## 📊 Dataset

This project uses the **TMDB 5000 Movie Dataset** which contains information about movies such as:

* Title
* Genres
* Cast
* Crew
* Overview

---

## 🚀 Features

* Select a movie from the dropdown
* Get top 5 similar movie recommendations
* Fast and interactive UI using Streamlit

---

## 🧠 How it works

* Data is cleaned and preprocessed
* Important features (genres, keywords, cast, crew) are combined
* Text is converted into vectors using **Bag of Words**
* Similarity is calculated using **Cosine Similarity**
* Top similar movies are recommended

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

---

## 📂 Project Structure

```
movie_recommender/
│
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
└── README.md
```

---

## ▶️ How to run locally

1. Clone the repository:

```
git clone https://github.com/your-username/movie-recommender.git
```

2. Go to the folder:

```
cd movie-recommender
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the app:

```
streamlit run app.py
```

---

## 🌐 Deployment

This project can be deployed using Streamlit Cloud.

---

## 💡 Future Improvements

* Add movie posters using TMDB API
* Improve UI design
* Add search functionality

---

## 👨‍💻 Author

Your Name

---

## ⭐ If you like this project

Give it a star on GitHub ⭐
