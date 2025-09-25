# TWEETS-SENTIMENT-ANALYSIS
Sentiment Analysis on Twitter data (Sentiment140) using Logistic Regression &amp; Naive Bayes. Includes text preprocessing, TF-IDF vectorization, model training, evaluation with confusion matrices, ROC curves, and feature importance visualization to classify tweets as positive or negative.

# 📊 Sentiment Analysis on Twitter Data (Sentiment140)
# 📌 Project Overview

This project performs Sentiment Analysis on Twitter data using the Sentiment140 dataset. The goal is to classify tweets as positive 😀 or negative 😞 by applying Natural Language Processing (NLP) and Machine Learning techniques.

The project was completed as part of my CodeAlpha Data Analytics Internship 🎓.

# 📂 Dataset

Source: Sentiment140 Dataset

Size: 1.6 million tweets (subset of 100,000 used for faster processing).

Columns:

target: sentiment label (0 = negative, 4 = positive → mapped to 0/1).

text: original tweet text.

clean_text: preprocessed tweet (after cleaning).

# 🛠️ Tools & Libraries

Python 🐍

pandas, numpy → data handling

nltk, re → text preprocessing

scikit-learn → machine learning models & evaluation

matplotlib → data visualization

# 🔎 Methodology

Data Cleaning

Removed URLs, mentions, special characters

Lowercased text, removed stopwords

Preprocessing

TF-IDF Vectorization for text representation

Model Training

Logistic Regression

Naive Bayes (MultinomialNB)

Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix 📉

ROC Curve & AUC Score 📈

Feature Importance (top positive & negative words)

# 📊 Results

Logistic Regression → 77% Accuracy

Naive Bayes → 75% Accuracy

# ✅ Logistic Regression performed slightly better.

Top Positive Words: love, great, amazing, fantastic
Top Negative Words: hate, bad, worst, sad

# 📈 Visualizations

✅ Confusion Matrices

✅ ROC Curve Comparison

✅ Feature Importance (word coefficients)

# 🚀 Insights

Tweets with words like love, amazing strongly predict positivity.

Tweets with words like hate, worst strongly predict negativity.

Logistic Regression generalizes slightly better than Naive Bayes.

Demonstrates how NLP + ML can extract public sentiment trends.

# 📌 Future Improvements

Use full 1.6M dataset for training.

Try advanced models (SVM, Random Forest).

Apply Deep Learning (LSTM, BERT) for better performance.

Deploy as a web app with Flask/Streamlit 🚀.
