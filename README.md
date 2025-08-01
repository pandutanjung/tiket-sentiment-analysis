# Sentiment Analysis on Tiket.com App Reviews

This project focuses on performing sentiment analysis on user reviews of the **Tiket.com** mobile application collected from the Google Play Store. The goal is to classify each review into one of three sentiment categories: **positive**, **neutral**, or **negative**, using Natural Language Processing (NLP) and machine learning techniques.

## 📌 Objectives

- To apply NLP techniques to real-world app review data
- To build a text classification model that accurately predicts sentiment
- To evaluate user feedback for potential product and service insights

## 🗂️ Dataset

- Source: Google Play Store (Tiket.com reviews)
- Format: Text reviews with manually labeled sentiment (positive, neutral, negative)

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Sastrawi (for stemming in Bahasa Indonesia)
- Scikit-learn
- TF-IDF Vectorizer
- Support Vector Machine (SVM)
- Matplotlib, Seaborn

## 🧪 Workflow

1. **Data Collection**
   - Reviews were scraped from the Tiket.com Google Play Store page.

2. **Text Preprocessing**
   - Case folding
   - Tokenization
   - Stopword removal
   - Stemming (Bahasa Indonesia)

3. **Feature Extraction**
   - TF-IDF (Term Frequency-Inverse Document Frequency)

4. **Modeling**
   - Support Vector Machine (SVM) classifier
   - Accuracy achieved: **93%**

5. **Evaluation**
   - Confusion matrix
   - Classification report

## 📈 Results

The SVM model achieved a high accuracy score of 93%, showing strong capability in distinguishing between positive, neutral, and negative user sentiments. The approach demonstrates the effectiveness of combining TF-IDF and SVM for sentiment classification in Bahasa Indonesia.

## 🧠 Key Learnings

- NLP preprocessing is crucial for high-quality text classification.
- TF-IDF is effective in transforming Indonesian text into machine-readable vectors.
- SVM works well for multi-class sentiment classification tasks.
