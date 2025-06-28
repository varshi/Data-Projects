# 📊 Sentiment Analysis using NLP

This project analyzes user sentiment from app reviews using Natural Language Processing (NLP) and Machine Learning. It compares traditional ensemble ML models with a deep learning model (RoBERTa) for robust sentiment classification.

---

## 📁 Project Structure

```
Sentiment Analysis using NLP/
├── Sentiment_Analysis_Final.ipynb     # Final Google Colab notebook
├── sample_app_reviews.csv             # Dataset used (offline-safe)
├── Project_Report.docx                # Formal project writeup
└── README.md                          # You're reading it!
```

---

## 🎯 Objective

> **Gauge user sentiment from app reviews to support product decision-making.**

- Preprocess labeled app review data
- Extract features using TF-IDF
- Reduce dimensions using PCA
- Train ensemble ML models (Random Forest + Gradient Boosting)
- Compare with deep learning model (RoBERTa)
- Achieved **93% accuracy** with only **2% Type I error**

---

## 🔍 What I Did

### 📥 1. Dataset Used
- Used a clean, offline-safe dataset with translated app reviews and sentiment labels (Positive/Negative)

### 🧹 2. Text Preprocessing
- Converted text to lowercase
- Removed stopwords and punctuation using NLTK
- Added a cleaned text column

### 📐 3. Feature Extraction
- Applied TF-IDF vectorization
- Reduced dimensionality with PCA for performance optimization

### 🤖 4. Ensemble ML Models
- Random Forest and Gradient Boosting
- Combined using soft-voting ensemble

### 📈 5. Evaluation Metrics
- Accuracy: **93%**
- Type I Error: **2%**
- Confusion matrix and classification report

### 🧠 6. RoBERTa Transformer Comparison
- Integrated `cardiffnlp/twitter-roberta-base-sentiment` using HuggingFace Transformers
- Compared traditional ML vs deep learning predictions

---

## 💻 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- NLTK
- HuggingFace Transformers
- Google Colab

---

## ▶️ How to Run

1. Open Colab and upload `sample_app_reviews.csv`
2. Open `Sentiment_Analysis_Final.ipynb`
3. Run all cells
4. View model performance and RoBERTa comparison

---

## ✅ Results

- The ensemble model delivered high accuracy with minimal Type I error
- RoBERTa provided comparable results using pre-trained sentiment model
- The project demonstrates the power of combining classical ML with transformers

---

## 🤝 Acknowledgements

- HuggingFace Transformers
- Cardiff NLP RoBERTa model
- Open-source Google Play user review datasets
- Scikit-learn and NLTK

