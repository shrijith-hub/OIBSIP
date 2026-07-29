# Sentiment Analysis using Machine Learning

## Overview

This project performs Sentiment Analysis on IMDb movie reviews using Natural Language Processing (NLP) techniques and Machine Learning.

The objective is to classify reviews as Positive or Negative using TF-IDF Vectorization and Logistic Regression.

---

## Dataset

IMDb Movie Reviews Dataset

- 50,000 movie reviews
- Balanced dataset
- Positive and Negative sentiments

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Pipeline

- Import Libraries
- Load Dataset
- Data Exploration
- Data Cleaning
- Train-Test Split
- TF-IDF Vectorization
- Logistic Regression
- Model Evaluation
- Custom Predictions

---

## Model Performance

Accuracy: **88.89%**

### Classification Report

| Class | Precision | Recall | F1-score |
|--------|-----------|--------|----------|
| Negative | 0.90 | 0.87 | 0.89 |
| Positive | 0.88 | 0.90 | 0.89 |

---

## Project Structure

```text
DataAnalytics-L4-SentimentAnalysis
│
├── dataset/
├── images/
├── output/
├── Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Results

The model successfully classifies movie reviews into Positive and Negative sentiments with approximately **89% accuracy**.

---

## Author

Shrijith K