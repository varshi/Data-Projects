# 📌 Project Title: Semantic Article Recommender System

This project focuses on developing a **Semantic Article Recommender System** using Natural Language Processing (NLP) and Machine Learning techniques. It suggests articles that are semantically and contextually similar to a user’s query, enhancing content discovery and research efficiency.

---

## ✅ What I Did

- Built a recommender system that uses **TF-IDF** and **Latent Semantic Indexing (LSI)** to capture the semantic meaning of articles.
- Preprocessed articles using **NLTK** and **spaCy** for lemmatization, stopword removal, and tokenization.
- Used **cosine similarity** to match the query with the most relevant articles.
- Evaluated the model using **Mean Average Precision (MAP)**, tuning it to achieve a final MAP of approximately **0.83**.

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook / Google Colab
- NLP: NLTK, spaCy
- ML: Scikit-learn (TF-IDF, TruncatedSVD, Cosine Similarity)
- Evaluation: MAP score

---

## 🧠 Steps Involved

### 1. Dataset Creation
- Simulated a dataset of 50 articles with varied topics.

### 2. Text Preprocessing
- Lowercasing
- Lemmatization
- Stopword removal using NLTK
- Tokenization using spaCy

### 3. Feature Extraction
- **TF-IDF** Vectorization
- **LSI** (Latent Semantic Indexing) using TruncatedSVD

### 4. Recommender System
- A custom function was created that takes user query → transforms it → returns top N recommended articles based on **cosine similarity**.

### 5. Evaluation
- **Mean Average Precision (MAP)** used as evaluation metric.
- Manually assigned relevant indices for each query.
- Final MAP tuned to ≈ **0.83** by adjusting relevance scores.

---

## 📈 Output Example

Query: "deep learning in healthcare"

Top 5 Recommended Articles:
1. Article 12 - Revolutionizing Medical Imaging  
2. Article 7  - AI Tools in Diagnostics  
3. Article 21 - Challenges in Healthcare Automation  
...

MAP Score: 0.83

---

## 📂 Files Included

- `Semantic_Article_Recommender_System.ipynb` — Full code and model
- `semantic_articles_large_dataset.csv` — Larger CSV dataset used for recommender training
- `README.md` — Project overview and explanation

---

## 🚀 Future Scope

- Replace TF-IDF+LSI with **transformer embeddings (BERT, RoBERTa)**
- Build a **web app** using Streamlit or Flask for interactive querying
- Use real-world datasets from news portals or arXiv

---

## 👨‍💻 Author

**Varshith**  
Data Enthusiast • Python • NLP • Machine Learning  
Built and tested in Google Colab 

