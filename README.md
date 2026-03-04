# 🎬 Movie Recommendation System 

## 📌 Project Overview
This project is a **content-based movie recommendation system** built using Python.  
It recommends similar movies based on features like **genres, keywords, cast, crew (director), and overview** using **natural language processing** and **cosine similarity**.

This is a great portfolio project for showcasing **Data Science, NLP, and Machine Learning skills**.

---

## ⚙️ Technologies & Libraries Used
- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK (Porter Stemmer)  
- Streamlit (optional for web app)  

---

## 🧠 Project Approach
1. **Data Loading:**  
   Loaded TMDB movies dataset (`tmdb_5000_movies.csv`) and credits dataset (`tmdb_5000_credits.csv`).

2. **Data Preprocessing:**  
   - Merged datasets on `title`.  
   - Selected relevant columns: `genres, keywords, cast, crew, overview`.  
   - Removed nulls.  
   - Extracted top 3 cast members.  
   - Extracted director from crew.

3. **Feature Engineering:**  
   - Converted all list-type columns into strings.  
   - Removed spaces from multi-word names (e.g., `Sam Worthington` → `SamWorthington`).  
   - Combined all features into a single column called `tags`.  
   - Applied **stemming** to reduce words to root forms.

4. **Text Vectorization:**  
   - Used **CountVectorizer** to convert text into numerical vectors (Bag of Words).  
   - Limited to **top 5000 words**.  

5. **Similarity Calculation:**  
   - Used **Cosine Similarity** to find similarity between movies.  

6. **Recommendation Function:**  
   - Built a function to input a movie title and get top 5 similar movies.



```bash
git clone <your-repo-link>
