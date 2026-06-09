# Bert-for-AG-news
# 📰 AG News Text Classification using BERT (DistilBERT)

This project is a deep learning text classification system that categorizes news articles into four classes using a pre-trained transformer model (DistilBERT). The model is fine-tuned on the AG News dataset and implemented in Google Colab using PyTorch and Hugging Face Transformers.

---

## 📌 Problem Statement

Automatically classify news articles into one of the following categories:

- World
- Sports
- Business
- Sci/Tech

---

## 🧠 Model Used

- **DistilBERT (distilbert-base-uncased)**
- Fine-tuned for **4-class text classification**
- Built using Hugging Face Transformers + PyTorch

---

## 📂 Dataset

- AG News Dataset (CSV version used due to compatibility issues with `datasets` library)
- Contains news headlines and descriptions
- Source: Public AG News dataset

---

## ⚙️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Pandas
- Scikit-learn
- Google Colab

---

## 🔄 Workflow

1. Load AG News dataset (CSV format)
2. Preprocess and combine title + description
3. Tokenize text using DistilBERT tokenizer
4. Create custom PyTorch Dataset
5. Fine-tune DistilBERT model
6. Evaluate performance using accuracy
7. Perform real-time predictions

---

## 📊 Model Training

- Epochs: 1
- Batch Size: 8
- Max Sequence Length: 128
- Optimized for Google Colab Free GPU

---
