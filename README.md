# Restaurant-Review-Sentiment-App
This project is a Natural Language Processing (NLP) and Machine Learning application that predicts whether a restaurant review is positive 🟢 or negative 🔴.
It includes both a Python script for model evaluation and a Streamlit web app for interactive prediction.

# 📂 Project Structure
├── Restaurant_Reviews_dummy.tsv   # Dataset (tab-separated file with Review + Label)
├── sentiment_analysis.py          # Core ML evaluation code
├── app.py                         # Streamlit app
└── README.md                      # Project documentation

# Features

Text Preprocessing: Cleans, tokenizes, and stems reviews.

Multiple Vectorizers:

TF-IDF

CountVectorizer

Machine Learning Models:

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest

Decision Tree

Support Vector Machine (SVM)

Naive Bayes

(Optional) XGBoost, LightGBM (if installed)

Model Evaluation:

Accuracy, Train/Test Bias, Variance

AUC Score

Confusion Matrix

Visualization of metrics with Seaborn

Interactive Web App:

Enter your review and get instant prediction

Probability score (if available)

Sidebar navigation for selecting models/vectorizers
