# 🕵️‍♂️ Fake News Classification using LSTM

Teaching machines to **smell lies in headlines**.  
Predicting if a news headline is **Fake 🚫** or **Real ✔️** using deep learning.

---

## 📌 Project Overview

This project builds a **Fake News Classifier** using an **LSTM (Long Short-Term Memory)** model.  
The model analyzes news headlines and learns **linguistic deception patterns**, detecting fake news based on context — not just keywords.

The purpose of the project is to understand how **sequential neural networks** learn and interpret text meaning in **NLP + Deep Learning**.

---

## 🚀 Features Implemented

- 🔹 **Text Cleaning**
  - Lowercasing, punctuation removal, regex cleaning, stopwords
- 🔹 **Tokenization & Sequencing**
  - Converting text to numerical padded sequences
- 🔹 **Embedding Layer**
  - Trainable word embeddings for semantic learning
- 🔹 **LSTM Model**
  - Context-aware prediction for Fake/Real headlines
- 🔹 **Performance Evaluation**
  - Accuracy, predictions on unseen data

---

## 📊 Dataset

You can access the dataset here 👇  
**https://drive.google.com/file/d/1CRpjYlIqH_7N3F1fQd889-tWebuPJjQm/view?usp=drive_link**

---

## 🧠 Why LSTM?

Because headlines are not just words —  
they are **sequences of intention**.

LSTM captures:

- Sentence flow
- Semantic transitions
- Context memory
- Tone & narrative structure

**It remembers what matters.**  
Unlike bag-of-words, it doesn’t forget the past.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NLTK**
- **TensorFlow / Keras**
- **Embedding Layer**
- **LSTM Network**
- **Google Colab**

---

## 📂 Project Workflow

1. Text preprocessing & cleaning
2. Tokenization & integer encoding
3. Padding sequences for uniform length
4. Trainable word embeddings
5. Build & train LSTM network
6. Evaluate model on unseen headlines
7. Predict Fake 🚫 or Real ✔️

---

## 📈 Results

| Metric | Score |
|--------|-------|
| Accuracy | **~93.5%** |

**Meaning:**  
The model learned the **patterns of deception**, not just keyword frequency.

---

## 💡 Example Predictions

```text
Input:  "Government launches AI project to revive economy"
Output: Real ✔️
