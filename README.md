# NLP Sentiment Analysis — Depression Detection from Tweets

A natural language processing project that classifies tweets as **Depressed** or **Not Depressed** using text preprocessing and machine learning models.

## Overview

This project applies NLP techniques to detect signs of depression in tweets. Text data is cleaned, lemmatized, and vectorized before being passed to multiple classifiers for comparison.

## Dataset

- **Source:** `sentiment_tweets3.csv`
- **Columns:** `text`, `Category` (Depressed / Not Depressed)
- **Size:** ~10,000+ tweets

## Models & Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 99.61% |
| Naive Bayes | 98.49% |
| Random Forest | 94.94% |

**Winner: Logistic Regression** with 99.61% accuracy on the test set.

## Tech Stack

- Python, Pandas, NumPy
- NLTK (lemmatization)
- Scikit-learn (CountVectorizer, models, metrics)
- Matplotlib (visualization)

## Project Structure
