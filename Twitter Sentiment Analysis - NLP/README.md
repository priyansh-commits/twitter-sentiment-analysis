# Twitter Sentiment Analysis using NLP & Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white)

A complete **Twitter Sentiment Analysis** project that classifies tweets as **Positive**, **Negative**, or **Neutral** using Natural Language Processing and Machine Learning.

## 📋 Project Overview

This project analyzes the sentiment of tweets using various machine learning models. It includes data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation.

### Key Features
- Text preprocessing (cleaning, tokenization, stopword removal)
- Exploratory Data Analysis with visualizations
- Multiple ML models comparison
- Performance metrics and confusion matrix
- Easy to understand Jupyter Notebook

## 🛠 Technologies Used
- **Python**
- **Pandas** & **NumPy** (Data Handling)
- **NLTK** / **TextBlob** (NLP)
- **Scikit-learn** (Machine Learning)
- **Matplotlib** & **Seaborn** (Visualization)
- **Jupyter Notebook**

## 📊 Dataset
- **Twitter Sentiments.csv** – Contains tweets with sentiment labels
- Dataset includes raw tweet text and corresponding sentiment



## 📈 Results

| Model | Accuracy | Precision | Recall | F1-Score |
|----------------------|---------:|----------:|--------:|---------:|
| Logistic Regression  | 94.78% | 74.83% | 38.28% | 50.65% |
| Random Forest        | 93.79% | 56.00% | 52.59% | **54.24%** |
| Naive Bayes          | 93.58% | 54.14% | **53.85%** | 53.99% |
| SVM                  | **94.76%** | **71.88%** | 41.14% | 52.33% |
### 📌 Best Performing Model

Among the four machine learning models, **Random Forest** achieved the highest **F1-score (54.24%)**, making it the best overall classifier for this imbalanced hate speech dataset. While Logistic Regression and SVM achieved slightly higher accuracy, Random Forest provided a better balance between precision and recall.



## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/priyansh-commits/twitter-sentiment-analysis.git
