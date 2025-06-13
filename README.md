#  Disaster Tweets Classification with BERTweet

This project demonstrates the use of the **BERTweet** transformer model for natural language classification of tweets.  
The task is to predict whether a tweet refers to a real disaster or not — a binary classification problem from a Kaggle competition.

---

## 📌 Project Overview

- **Dataset**: [Kaggle - NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)
- **Goal**: Predict if a tweet is about a real disaster (1) or not (0)
- **Model used**: **BERTweet** (RoBERTa architecture, pretrained on tweets)
- **Evaluation**: Accuracy / F1-score (depending on use case)

---

## 📂 Files

- `nlp-disaster-tweets-bertweet.ipynb` – Jupyter Notebook with preprocessing, training and evaluation

---

##  Technologies Used

- `Python 3`
- `pandas`, `numpy`
- `transformers` by Hugging Face
- `tensorflow`
- `sklearn` (for evaluation)
- `Jupyter Notebook`

---

##  Model Summary

| Component         | Description                                    |
|------------------|------------------------------------------------|
| Tokenizer        | `vinai/bertweet-base`                          |
| Encoder Model    | Pretrained BERTweet (based on RoBERTa)         |
| Text length      | Truncated to 128 tokens                        |

---

