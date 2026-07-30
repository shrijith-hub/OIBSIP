# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project predicts the quality of red wine using Machine Learning classification algorithms based on its physicochemical properties.

The complete machine learning pipeline includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation.

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (Level 2 - Task 2).**

---

## 📂 Dataset

**Dataset:** Wine Quality Dataset (Red Wine)

**Source:** UCI Machine Learning Repository

The dataset contains physicochemical properties of Portuguese red wines, including:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

Target Variable:

- Wine Quality

---

## 🎯 Project Objectives

- Understand the dataset
- Perform Exploratory Data Analysis (EDA)
- Visualize feature distributions
- Analyze feature correlations
- Perform feature engineering
- Train multiple machine learning models
- Compare model performance
- Identify important features affecting wine quality

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Missing Value Analysis
- Duplicate Record Removal
- Class Distribution
- Histograms
- Boxplots
- Correlation Heatmap
- Alcohol Distribution
- Alcohol vs Quality
- Volatile Acidity vs Quality

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

---

## ⭐ Feature Importance

Feature importance was extracted using the Random Forest model to identify the most influential physicochemical properties affecting wine quality.

---

## 📁 Project Structure

```
Wine-Quality-Prediction/
│
├── data/
│   └── winequality-red.csv
│
├── images/
│   ├── class_distribution.png
│   ├── alcohol_distribution.png
│   ├── alcohol_vs_quality.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix_rf.png
│   ├── confusion_matrix_sgd.png
│   ├── confusion_matrix_svc.png
│   ├── feature_importance.png
│   └── model_accuracy_comparison.png
│
├── Wine_Quality_Prediction.ipynb
├── model_comparison.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📌 Results

- Successfully trained and evaluated three machine learning models.
- Random Forest achieved the best overall performance.
- Alcohol and Volatile Acidity were among the most important features.
- The project demonstrates an end-to-end machine learning workflow for classification.

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- SMOTE for handling class imbalance
- XGBoost
- LightGBM
- CatBoost

---

## 👨‍💻 Author

**Shrijith K**

AI & Data Science Student

Oasis Infobyte Data Analytics Internship