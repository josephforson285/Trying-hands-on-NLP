# NLP Classification with PySpark MLlib

This project applies **Natural Language Processing (NLP)** and **machine learning** using **PySpark MLlib** to predict whether a Kickstarter project will be **successful or failed** based on its text description.

---

## Overview
- Clean and preprocess raw text data
- Tokenize and remove stopwords
- Convert text into numerical features
- Train and evaluate multiple classifiers
- Compare different text vectorization methods

---

## Dataset
- **Source**: Kaggle – Kickstarter NLP Dataset  
- **Text**: Project blurb  
- **Target**: `successful` vs `failed`

---

## Methods
- **Text Processing**: RegexTokenizer, StopWordsRemover
- **Feature Engineering**:
  - HashingTF
  - TF-IDF
  - Word2Vec
- **Models**:
  - Logistic Regression
  - Naive Bayes
  - Decision Tree
  - Random Forest
  - SVM
  - Neural Network
- **Workflow**: Spark ML Pipelines + Cross-Validation

 
