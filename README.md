# 🧠 Sentiment Analysis on Amazon Customer Reviews

This project performs **Sentiment Analysis** on Amazon customer reviews using two popular NLP approaches:

- **NLTK's VADER** (Valence Aware Dictionary and sEntiment Reasoner)
- 🤗 **Hugging Face Transformers** with the **RoBERTa** model

The goal is to classify each review into **Positive**, **Negative**, or **Neutral** sentiment and **compare the performance** of both methods.

---

## 🔍 Project Overview

Sentiment analysis is a key technique in Natural Language Processing (NLP) for understanding opinions and emotions in text data. In this project, we:

- Use VADER from NLTK for rule-based sentiment scoring.
- Use a pretrained RoBERTa model from Hugging Face Transformers for deep learning-based classification.
- Compare the outputs and performance of both models on Amazon product review data.

---

## 📦 Tech Stack

- **Python 3.8+**
- **NLTK (VADER)**
- **Hugging Face Transformers (RoBERTa)**
- **Pandas, NumPy, Matplotlib/Seaborn** for data processing and visualization
- **Torch (PyTorch backend)**

---

## 🗂️ Dataset

The dataset used is a collection of **Amazon customer reviews**. Each entry includes:

- Review Text
- (Optional) Rating
- Ground truth sentiment (for evaluation)

You can use your own dataset or download a sample dataset like the [Amazon Review Data (2018)](https://nijianmo.github.io/amazon/index.html) from UCSD.

---

## 🚀 Setup & Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/sentiment-analysis-amazon.git
cd sentiment-analysis-amazon
