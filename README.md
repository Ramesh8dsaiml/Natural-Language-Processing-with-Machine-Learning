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

This repository showcases my complete learning journey in **Classical Natural Language Processing (NLP)** using **Python**, **NLTK**, and **Scikit-Learn**.

The repository covers the complete NLP pipeline—from text preprocessing and feature extraction to building and evaluating machine learning models on a real-world text classification dataset.

This project was created to strengthen my NLP fundamentals before moving to **Deep Learning**, **Transformers**, and **Large Language Models (LLMs)**.

---

# 🚀 Project Highlights

- 📚 Complete NLP Notes
- 💻 Hands-on NLP Practice
- 📊 Real Dataset Implementation
- 🧹 Complete Text Preprocessing
- 🔤 Feature Extraction Techniques
- 🤖 Machine Learning Text Classification
- 📈 Model Performance Comparison
- 🎯 Interview-Oriented Concepts

---

# 📂 Repository Structure

```
Natural-Language-Processing-with-Machine-Learning
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

# 📚 NLP Topics Covered

## 🧹 Text Preprocessing

- Lowercase Conversion
- Remove Punctuation
- Remove Numbers
- Remove HTML Tags
- Remove URLs
- Remove Extra Spaces
- Remove Special Characters
- Remove Emojis
- Complete Cleaning Function

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
- POS Tag Identification
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
- TF-IDF (Term Frequency – Inverse Document Frequency)

---

# 💻 Practical Implementation

Implemented all NLP concepts using **Python**, **NLTK**, and **Scikit-Learn**, including:

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

---

# 🤖 Machine Learning Text Classification

A complete end-to-end text classification pipeline was built using a real-world dataset.

## Workflow

```
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Train-Test Split
      │
      ▼
Feature Extraction
      ├── Bag of Words (CountVectorizer)
      └── TF-IDF (TfidfVectorizer)
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

# 🤖 Machine Learning Models Used

- Multinomial Naive Bayes
- Logistic Regression

---

# 📊 Model Performance

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

The experimental results indicate that **TF-IDF combined with Logistic Regression** achieved the highest accuracy among the evaluated combinations.

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
- One-Hot Encoding
- Bag of Words
- CountVectorizer
- N-Grams
- TF-IDF
- Feature Engineering
- Text Classification
- Logistic Regression
- Multinomial Naive Bayes
- Model Evaluation
- Scikit-Learn
- NLTK

---

# 📈 Learning Outcomes

Through this repository, I learned how to:

- Preprocess raw text data.
- Build complete text preprocessing pipelines.
- Apply feature extraction techniques.
- Convert text into numerical representations.
- Train and evaluate machine learning models.
- Compare multiple NLP feature extraction techniques.
- Build an end-to-end text classification workflow.

---

# 🚀 Future Roadmap

The next phase of my NLP learning journey includes:

- Word2Vec
- FastText
- GloVe
- Deep Learning for NLP
- RNN
- LSTM
- GRU
- Seq2Seq Models
- Attention Mechanism
- Transformers
- BERT
- GPT
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)

---

# 📌 Repository Highlights

✅ Complete NLP Notes

✅ Hands-on Practice

✅ Real Dataset Implementation

✅ Feature Extraction

✅ Multiple Machine Learning Models

✅ Accuracy Comparison

✅ Interview-Oriented Learning

✅ End-to-End NLP Pipeline

---

# 🤝 Contributing

Suggestions and improvements are always welcome.

If you find this project useful, feel free to fork the repository or open an issue.

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
