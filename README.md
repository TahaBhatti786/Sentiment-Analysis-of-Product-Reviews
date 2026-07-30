# Sentiment Analysis of Product Reviews

## About the Project

This project was developed as part of my Machine Learning Internship at **CanvasGali**. The objective is to classify Amazon Alexa product reviews into positive or negative sentiments using Natural Language Processing (NLP) and classical machine learning techniques.

The project covers the complete machine learning pipeline, including data preprocessing, exploratory data analysis, feature extraction, model training, evaluation, and testing on unseen reviews.

---

## Project Objectives

- Perform sentiment analysis on product reviews.
- Clean and preprocess textual data.
- Convert text into numerical features using Bag of Words and TF-IDF.
- Train and compare multiple machine learning models.
- Evaluate model performance using standard classification metrics.
- Predict sentiment for new customer reviews.

---

## Dataset

The project uses the **Amazon Alexa Reviews** dataset obtained from Kaggle.

**Dataset Format:** TSV (Tab-Separated Values)

### Dataset Columns

| Column | Description |
|---------|-------------|
| rating | Customer rating (1–5 stars) |
| date | Review date |
| variation | Product variation |
| verified_reviews | Customer review text |
| feedback | Sentiment label (Target Variable) |

### Target Variable

| Value | Sentiment |
|------:|-----------|
| 1 | Positive |
| 0 | Negative |

---

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Joblib

---

## Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression
- Multinomial Naive Bayes

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Text Cleaning
4. Stopword Removal
5. Lemmatization
6. Exploratory Data Analysis (EDA)
7. Bag of Words Feature Extraction
8. TF-IDF Feature Extraction
9. Train-Test Split
10. Logistic Regression Training & Evaluation
11. Multinomial Naive Bayes Training & Evaluation
12. Model Comparison
13. Testing on Custom Reviews
14. Saving the Trained Model

---

## Project Structure

```text
Sentiment-Analysis-of-Product-Reviews/
│
├── dataset/
│   └── amazon_alexa.tsv
│
├── notebooks/
│
├── models/
│   ├── sentiment_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── outputs/
│
├── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Features

- Data preprocessing using NLTK
- Text cleaning and normalization
- Stopword removal
- Lemmatization
- Exploratory Data Analysis (EDA)
- Bag of Words implementation
- TF-IDF vectorization
- Logistic Regression classifier
- Multinomial Naive Bayes classifier
- Model performance comparison
- Prediction on custom reviews
- Model serialization using Joblib

---

## Model Evaluation

Both machine learning models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

The evaluation results were compared to identify the better-performing model for sentiment classification.

---

## Future Improvements

Possible enhancements for this project include:

- Hyperparameter tuning
- Cross-validation
- Handling class imbalance
- Testing additional machine learning algorithms
- Deploying the model using Streamlit or Flask

---

## Project Status

**Status:** Completed

This project was successfully completed as part of the **CanvasGali Machine Learning Internship Program**.

### Key Highlights

- NLP-based sentiment analysis
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Bag of Words and TF-IDF feature extraction
- Logistic Regression and Multinomial Naive Bayes models
- Model evaluation using Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC Curve
- Custom review prediction
- Model saving using Joblib

---

This Project is created under CanvasGali Internship Program.

---
