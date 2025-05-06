# Tweet Sentiment Analyzer

A machine learning-based sentiment analysis tool for classifying tweets as positive or negative using TF-IDF and Logistic Regression.

## 📌 Overview

This project demonstrates how to process and analyze tweet data using a simple yet effective Natural Language Processing (NLP) pipeline. The model uses:

- **TF-IDF Vectorization** for feature extraction
- **Logistic Regression** for classification

It achieves an accuracy of **~79.8% on training** and **~77.6% on test data**.

## 🛠️ Features

- Preprocessing of text data
- Vectorization using `TfidfVectorizer`
- Sentiment classification
- Model serialization with `pickle`
- Easy prediction on new tweet samples

## 🧪 Tech Stack

- Python
- Scikit-learn
- NumPy
- Jupyter Notebook
- Pickle

## 📊 Model Performance

| Metric         | Value         |
|----------------|---------------|
| Training Accuracy | 79.87%     |
| Test Accuracy     | 77.66%     |

## 🚀 Usage

1. Clone the repository:

```bash
git clone https://github.com/shameel0505/tweet-sentiment-analyzer.git
cd tweet-sentiment-analyzer
