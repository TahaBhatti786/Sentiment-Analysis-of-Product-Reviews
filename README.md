````markdown
# Sentiment Analysis of Product Reviews

## About the Project

This project is part of my Machine Learning internship. The goal is to build a sentiment analysis model that can classify Amazon Alexa product reviews as either positive or negative.

The project follows a typical machine learning workflow, starting from data preprocessing and exploratory analysis to model training, evaluation, and testing.

---

## Project Objectives

- Analyze customer reviews using Natural Language Processing (NLP).
- Clean and preprocess review text.
- Convert text into numerical features using TF-IDF.
- Train and compare different machine learning models.
- Evaluate the models using classification metrics.
- Test the final model on new reviews.

---

## Dataset

The project uses the **Amazon Alexa Reviews** dataset from Kaggle.

**File Format:** TSV (Tab-Separated Values)

### Main Columns

| Column | Description |
|---------|-------------|
| rating | Customer rating (1–5 stars) |
| date | Date of the review |
| variation | Product variation |
| verified_reviews | Review text |
| feedback | Sentiment label |

### Target Variable

| Value | Sentiment |
|------:|-----------|
| 1 | Positive |
| 0 | Negative |

---

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib

---

## Machine Learning Models

The following models will be implemented and compared:

- Logistic Regression
- Multinomial Naive Bayes

---

## Project Workflow

1. Load the dataset
2. Explore the data
3. Clean and preprocess review text
4. Perform exploratory data analysis (EDA)
5. Convert text into numerical features (Bag of Words & TF-IDF)
6. Train machine learning models
7. Evaluate model performance
8. Test the model using custom reviews
9. Save the trained model

---

## Project Structure

```text
Sentiment-Analysis-of-Product-Reviews/
│
├── dataset/
│   └── amazon_alexa_reviews.tsv
│
├── notebooks/
│
├── outputs/
│
├── models/
│
├── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Progress

- ✅ Repository created
- ✅ Project structure completed
- ✅ Dataset added
- ⏳ Data loading
- ⏳ Data exploration
- ⏳ Text preprocessing
- ⏳ Exploratory Data Analysis
- ⏳ Feature extraction
- ⏳ Model training
- ⏳ Model evaluation
- ⏳ Testing on custom reviews
- ⏳ Project documentation

---

## Future Work

Some improvements that can be explored later include:

- Hyperparameter tuning
- Cross-validation
- Streamlit web application for predictions
- Testing additional machine learning algorithms

---

This Project is created under CanvasGali Internship Program.


