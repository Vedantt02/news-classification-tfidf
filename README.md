# 📰 News Classification using TF-IDF

## 📌 Overview

This project focuses on building a **text classification model** using classical Machine Learning techniques. The goal is to classify news articles into predefined categories based on their content.

This serves as a strong foundation in **Natural Language Processing (NLP)** and demonstrates how traditional approaches can still achieve high performance.

---

## 📊 Dataset

* Dataset: BBC News Dataset
* Total Samples: ~2225 articles
* Categories:

  * Business
  * Entertainment
  * Politics
  * Sport
  * Tech

🔗 Dataset Link: https://www.kaggle.com/datasets/yufengdev/bbc-fulltext-and-category

---

## 🎯 What I Learned

Through this project, I focused on:

* Understanding **text preprocessing techniques**
* Applying **TF-IDF vectorization**
* Building baseline models like:

  * Logistic Regression
  * Naive Bayes
* Evaluating models using:

  * Precision
  * Recall
  * F1-score
* Performing **error analysis using confusion matrix**
* Understanding **model limitations in handling context**

---

## ⚙️ Approach

### 1. Data Preprocessing

* Lowercasing
* Removing punctuation
* Cleaning text

### 2. Feature Engineering

* TF-IDF Vectorization
* `max_features = 5000`

### 3. Model Training

* Logistic Regression (primary model)
* Naive Bayes (comparison)

### 4. Evaluation

* Achieved ~96–97% accuracy
* Used classification report and confusion matrix

---

## 📈 Results

* Logistic Regression performed strongly across all categories
* Sports and Politics were easiest to classify
* Business showed slight confusion with Politics

---

## ⚠️ Limitations

* TF-IDF does not understand context
* Words are treated independently (bag-of-words approach)
* Struggles with ambiguous sentences

---

## 🧠 Key Takeaway

> Classical ML models can perform extremely well on structured text data, but they lack contextual understanding.

---

## 🚀 Future Work

* Improve feature engineering using n-grams
* Compare with Deep Learning models (BERT)
* Build real-world NLP applications

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* Pandas
* Matplotlib / Seaborn

---

## 🙌 Author

Vedant
CSE Student | ML & DL Enthusiast
