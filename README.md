# 🧠 Natural Language Processing (NLP) with Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)

</p>

---

# 📖 About The Project

This repository demonstrates my complete learning journey in **Classical Natural Language Processing (NLP)** using **Python**, **NLTK**, and **Scikit-Learn**.

The project covers the complete NLP workflow, including text preprocessing, feature extraction, and machine learning-based text classification using a real-world dataset.

The primary objective of this repository is to build a strong foundation in NLP before moving towards **Deep Learning**, **Transformers**, and **Large Language Models (LLMs)**.

---

# 🚀 Repository Highlights

- 📚 Complete NLP Notes
- 💻 Hands-on Practice Notebook
- 📊 Real Dataset Implementation
- 🧹 Text Preprocessing
- 🔤 Feature Extraction
- 🤖 Machine Learning Text Classification
- 📈 Model Performance Comparison
- 🎯 Interview-Oriented Concepts

---

# 📂 Repository Structure

```
Natural-Language-Processing-with-Machine-Learning/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── NLP.pdf
├── train.txt
│
├── 01_NLP_Practice.ipynb
└── 02_Text_Classification_BoW_TFIDF_LogisticRegression.ipynb
```

---

# 📚 NLP Concepts Covered

## 🧹 Text Preprocessing

- Lowercase Conversion
- Remove Punctuation
- Remove Numbers
- Remove HTML Tags
- Remove URLs
- Remove Extra Spaces
- Remove Special Characters
- Remove Emojis
- Complete Text Cleaning Function

---

## ✂️ Tokenization

- Word Tokenization
- Sentence Tokenization

---

## 🚫 Stopword Removal

- English Stopwords
- Custom Stopwords

---

## 🌱 Stemming

- Porter Stemmer
- Lancaster Stemmer
- Snowball Stemmer

---

## 📖 Lemmatization

- WordNet Lemmatizer
- POS-aware Lemmatization

---

## 📝 POS Tagging

- Parts of Speech
- Practical Examples

---

## 🧩 Chunking

- Noun Phrase Chunking
- Chunk Grammar
- Parse Tree

---

## 🏷️ Named Entity Recognition (NER)

- PERSON
- ORGANIZATION
- LOCATION
- DATE
- MONEY
- GPE

---

## 📊 Frequency Distribution

- Word Frequency Analysis
- Most Frequent Words

---

# 🔤 Feature Extraction Techniques

- One-Hot Encoding
- Bag of Words (BoW)
- CountVectorizer
- N-Grams
- TF-IDF (Term Frequency–Inverse Document Frequency)

---

# 💻 Practical Implementation

The repository includes practical implementations of:

- Text Cleaning
- Tokenization
- Stopword Removal
- Stemming
- Lemmatization
- POS Tagging
- Chunking
- Named Entity Recognition
- Frequency Distribution
- One-Hot Encoding
- Bag of Words
- CountVectorizer
- N-Grams
- TF-IDF

using **Python**, **NLTK**, and **Scikit-Learn**.

---

# 📂 Dataset

This project uses the **Emotions Dataset for NLP**, a publicly available dataset from Kaggle.

**Dataset Source:**

https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp

### Dataset Information

- Dataset Type: Emotion Text Classification
- Language: English
- Source: Kaggle
- Purpose: Educational and Practice

The dataset was used to understand and implement an end-to-end NLP text classification pipeline and compare different feature extraction techniques and machine learning algorithms.

---

# 🤖 Machine Learning Text Classification

A complete NLP text classification pipeline was implemented using the above dataset.

## Project Workflow

```
Load Dataset
        │
        ▼
Text Cleaning
        │
        ▼
Train-Test Split
        │
        ▼
Feature Extraction
   ├── Bag of Words
   └── TF-IDF
        │
        ▼
Machine Learning Models
   ├── Multinomial Naive Bayes
   └── Logistic Regression
        │
        ▼
Prediction
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

---

# 🤖 Machine Learning Models

- Multinomial Naive Bayes
- Logistic Regression

---

# 📊 Model Performance Comparison

| Feature Extraction | Machine Learning Model | Accuracy |
|--------------------|------------------------|---------:|
| Bag of Words (CountVectorizer) | Multinomial Naive Bayes | **76.81%** |
| TF-IDF (TfidfVectorizer) | Multinomial Naive Bayes | **66.09%** |
| TF-IDF (TfidfVectorizer) | Logistic Regression | **86.28% 🏆** |

---

# 🏆 Best Performing Model

| Feature Extraction | Model | Accuracy |
|--------------------|-------|---------:|
| **TF-IDF** | **Logistic Regression** | **86.28%** |

The comparison shows that **TF-IDF with Logistic Regression** achieved the highest accuracy on the selected dataset.

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- NLTK
- Scikit-Learn
- Regular Expressions (`re`)
- Jupyter Notebook

---

# 📚 Python Libraries

```python
import re
import string
import numpy as np
import pandas as pd

import nltk

from sklearn.model_selection import train_test_split

from sklearn.feature_extraction.text import CountVectorizer
from sklearn.feature_extraction.text import TfidfVectorizer

from sklearn.naive_bayes import MultinomialNB
from sklearn.linear_model import LogisticRegression

from sklearn.metrics import accuracy_score
```

---

# 🎯 Skills Demonstrated

- Natural Language Processing (NLP)
- Text Preprocessing
- Text Cleaning
- Tokenization
- Stopword Removal
- Stemming
- Lemmatization
- POS Tagging
- Chunking
- Named Entity Recognition
- Frequency Distribution
- Feature Engineering
- One-Hot Encoding
- Bag of Words
- CountVectorizer
- N-Grams
- TF-IDF
- Text Classification
- Logistic Regression
- Multinomial Naive Bayes
- Model Evaluation
- Scikit-Learn
- NLTK

---

# 📈 Learning Outcomes

After completing this repository, I learned how to:

- Build complete text preprocessing pipelines.
- Convert raw text into numerical features.
- Apply Bag of Words and TF-IDF for feature extraction.
- Train and evaluate machine learning models.
- Compare different NLP feature extraction techniques.
- Build an end-to-end text classification workflow.

---

# 🚀 Future Roadmap

The next phase of my NLP journey includes:

- Word2Vec
- FastText
- GloVe
- Deep Learning for NLP
- RNN
- LSTM
- GRU
- Transformers
- BERT
- GPT
- Large Language Models (LLMs)

---

# 📌 Repository Highlights

- ✅ Complete NLP Notes
- ✅ Hands-on Practice
- ✅ Real Dataset Implementation
- ✅ Feature Extraction Techniques
- ✅ Multiple Machine Learning Models
- ✅ Model Performance Comparison
- ✅ End-to-End NLP Pipeline

---

# 📌 Disclaimer

This repository is created for **educational and learning purposes**.

The dataset used in this project is publicly available on Kaggle. All credit for the dataset goes to its original creator.

Dataset:
https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp

---

# ⭐ Support

If you found this repository helpful, please consider giving it a **⭐ Star**.

---

# 👨‍💻 Author

## Ramesh Kumar

**B.Tech – Artificial Intelligence & Data Science**

### Areas of Interest

- Data Science
- Machine Learning
- Natural Language Processing
- Deep Learning
- Large Language Models (LLMs)

---

## 🚀 Happy Learning!
