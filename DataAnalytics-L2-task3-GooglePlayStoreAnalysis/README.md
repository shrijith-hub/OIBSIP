# 📱 Google Play Store Analysis

## 📌 Project Overview

This project analyzes the **Google Play Store** dataset to uncover valuable insights into app categories, ratings, installs, pricing, estimated revenue, and user sentiment. The analysis follows a complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), visualization, and sentiment analysis.

The objective is to understand the characteristics of successful applications and identify trends that can support data-driven business decisions.

---

## 🎯 Objectives

* Clean and preprocess the Google Play Store dataset.
* Handle missing values and duplicate records.
* Perform exploratory data analysis (EDA).
* Analyze app categories, ratings, installs, and pricing.
* Estimate potential revenue for paid applications.
* Perform sentiment analysis on user reviews using VADER.
* Visualize findings using Matplotlib, Seaborn, and Plotly.
* Generate meaningful business insights.

---

## 📂 Dataset

The project uses two datasets:

* **googleplaystore.csv** – Information about Google Play Store applications.
* **googleplaystore_user_reviews.csv** – User reviews and translated review text.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* NLTK (VADER Sentiment Analyzer)
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

* Imported application dataset.
* Imported user reviews dataset.

### 2. Data Cleaning

* Removed duplicate records.
* Handled missing values.
* Converted data types.
* Cleaned:

  * Reviews
  * Installs
  * Price
  * Size
  * Last Updated
* Removed corrupted records.

### 3. Exploratory Data Analysis

Performed analyses including:

* Number of apps by category
* Rating distribution
* Average rating by category
* Total installs by category
* App size vs installs
* Free vs paid applications
* Price distribution
* Correlation heatmap

### 4. Revenue Estimation

Estimated revenue using:

> **Estimated Revenue = Price × Installs**

Identified the top revenue-generating paid applications.

### 5. Sentiment Analysis

Used the **VADER Sentiment Analyzer** to classify reviews into:

* Positive
* Neutral
* Negative

Analyzed sentiment trends across different app categories.

### 6. Interactive Visualizations

Created interactive dashboards using Plotly to explore:

* Category distribution
* Rating distribution
* Size vs installs
* Estimated revenue

---

## 📈 Key Insights

* The **Family** category contains the highest number of applications.
* Most apps have ratings between **4.0 and 4.5**.
* Free applications dominate the Google Play Store.
* App size has little impact on install count.
* Premium-priced apps with high installs generate the greatest estimated revenue.
* User reviews are predominantly positive, indicating overall customer satisfaction.
* Sentiment analysis helps identify categories that may require quality improvements.

---

## 📁 Project Structure

```text
DataAnalytics-L2-task3-GooglePlayStoreAnalysis/
│
├── data/
│   ├── googleplaystore.csv
│   ├── googleplaystore_user_reviews.csv
│   ├── googleplaystore_cleaned.csv
│   └── googleplaystore_reviews_cleaned.csv
│
├── notebooks/
│   └── Google_Play_Store_Analysis.ipynb
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/DataAnalytics-L2-task3-GooglePlayStoreAnalysis.git
```

2. Navigate to the project directory.

```bash
cd DataAnalytics-L2-task3-GooglePlayStoreAnalysis
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the notebook and run all cells.

---

## 📚 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Sentiment Analysis
* Business Insight Generation
* Python Programming

---

## 🚀 Future Improvements

* Build a machine learning model to predict app ratings.
* Develop a Streamlit dashboard for interactive analysis.
* Perform topic modeling on user reviews.
* Analyze trends across app update history.
* Deploy the project as a web application.

---

## 👨‍💻 Author

**Shrijith K**

B.Tech – Artificial Intelligence & Data Science

---

## 📄 License

This project is licensed under the MIT License.
