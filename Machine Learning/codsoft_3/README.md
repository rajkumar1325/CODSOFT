# 📩 SMS Spam Detection


## SPAM SMS DETECTION
**Problem Statement:** _Build an AI model that can classify SMS messages as spam or legitimate. Use techniques like TF-IDF or word embeddings with classifiers like Naive Bayes, Logistic Regression, or Support VectorMachines to identify spam messages_
[Dataset](https://drive.google.com/drive/folders/1toOaQ1COFPPoZxZZ6aBuMIOXXSs7R9b7?usp=drive_link)





![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data-green?style=for-the-badge&logo=pandas)
![Accuracy](https://img.shields.io/badge/Accuracy-95.25%25-brightgreen?style=for-the-badge)

> A machine learning model that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing and Logistic Regression — achieving **95.25% accuracy** on 5,572 real messages.

---

## 🔄 Pipeline

```
Raw SMS Dataset
      ↓
Load & Decode (latin-1)
      ↓
Rename Columns (v1 → label, v2 → text)
      ↓
Label Encoding (ham → 0, spam → 1)
      ↓
Train / Test Split (80/20)
      ↓
TF-IDF Vectorization
      ↓
Logistic Regression Model
      ↓
Accuracy: 95.25% ✅
```

---

## ✨ Features

- Trained on **5,572 real SMS messages** from the UCI SMS Spam Collection
- **TF-IDF Vectorization** to convert text into numerical features
- **Logistic Regression** classifier for binary classification
- Evaluated using accuracy, precision, recall & F1-score
- Supports **custom message prediction** in real-time

---

## 📊 Model Performance

| Metric | Ham (0) | Spam (1) |
|--------|---------|----------|
| Precision | 0.95 | 0.97 |
| Recall | 1.00 | 0.67 |
| F1-Score | 0.97 | 0.79 |
| **Accuracy** | — | **95.25%** |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `pandas` | Data loading & preprocessing |
| `scikit-learn` | TF-IDF, Logistic Regression, metrics |
| `Google Colab` | Development environment |

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/rajkumar1325/CODSOFT.git
cd CODSOFT
```

2. Open the notebook:
```
SmsSpamDetection.ipynb
```

3. Upload `spam.csv` dataset and run all cells.

---

## 🧪 Custom Prediction

```python
messages = ["Free entry in a contest!"]
messages_tfidf = vectorizer.transform(messages)
predictions = model.predict(messages_tfidf)
# Output: Spam ✅
```

---

## 🤝 Connect

**Raj Kumar** — B.Tech CSE 2026

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rajkumar0104-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/rajkumar0104/)
[![GitHub](https://img.shields.io/badge/GitHub-rajkumar1325-black?style=flat&logo=github)](https://github.com/rajkumar1325)
[![Email](https://img.shields.io/badge/Email-rajkumar.rk0104@gmail.com-red?style=flat&logo=gmail)](mailto:rajkumar.rk0104@gmail.com)
