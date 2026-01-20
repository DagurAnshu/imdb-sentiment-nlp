# IMDb Sentiment NLP

This repository contains an end-to-end sentiment analysis project on IMDb movie reviews.
It starts with **classical NLP techniques** and is designed to be extended later to
**deep learning** and **large language models (LLMs)**.

The goal of this project is not just accuracy, but a clear, reproducible NLP pipeline
that shows how raw text is transformed into meaningful predictions.

---

## 📌 Project Overview

- Dataset: IMDb Movie Reviews (Hugging Face)
- Task: Binary sentiment classification (Positive / Negative)
- Current Approach: Classical NLP
- Future Scope: Deep Learning & LLM-based models

---

## 🧠 Current Implementation (Classical NLP)

The current version uses a well-established classical NLP pipeline:

1. **Minimal Text Cleaning**
   - Remove HTML tags
   - Normalize whitespace
   - Preserve sentiment-critical words (e.g. negations)

2. **Text Representation**
   - TF-IDF Vectorization
   - Unigrams + Bigrams (captures phrases like *"not good"*)
   - Rare and overly common tokens filtered

3. **Model**
   - Logistic Regression
   - Strong baseline for high-dimensional sparse text data

4. **Prediction**
   - Supports interactive prediction on custom user input

---

## 📊 Results

- Test Accuracy: **~88–90%** on the IMDb test set
- Performance is comparable to standard classical NLP baselines

> Note: Accuracy is reported only after ensuring identical preprocessing for
> training data, test data, and user input.

---

## 🗂 Repository Structure (Planned)


