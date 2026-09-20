# 📩 Spam Message Detection using Machine Learning

## 📌 Project Overview

This project focuses on building machine learning models to classify text messages as **Spam** or **Ham (Not Spam)**.

The project applies different Natural Language Processing (NLP) techniques and machine learning algorithms to transform text messages into numerical features and evaluate their ability to distinguish between spam and legitimate messages.

The analysis includes:

- Text preprocessing and label encoding
- Train-test splitting
- Count Vectorization
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Support Vector Classifier (SVC)
- Logistic Regression
- Character-level n-grams
- Additional text-based features such as:
  - Message length
  - Number of digits
  - Number of non-word characters
- ROC-AUC evaluation

---

## 🎯 Objective

The main objective of this project is to develop and evaluate machine learning approaches for automatically identifying whether a text message is:

- **Ham (0)** → Legitimate message
- **Spam (1)** → Spam message

---

## 📊 Dataset

The project uses a spam message dataset containing text messages labeled as either `ham` or `spam`.

The original dataset columns are renamed as:

| Original Column | New Column | Description |
|---|---|---|
| `v1` | `target` | Message classification |
| `v2` | `text` | Text message |

The target variable is converted into binary values:

```text
Ham  → 0
Spam → 1
