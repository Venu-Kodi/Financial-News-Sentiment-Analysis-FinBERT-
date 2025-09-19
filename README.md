# Financial News Sentiment Analysis using FinBERT + Optuna Fine-Tuning

This repository contains an **end-to-end project** for performing **Financial News Sentiment Analysis** using **FinBERT**, a BERT-based model pretrained on financial text. It also includes **Optuna-based hyperparameter tuning** to fine-tune the model for better performance on your dataset.

---

## 🚀 Project Overview

Financial news often influences stock prices, market sentiment, and investor decisions. This project demonstrates:

- Loading and exploring a financial news dataset.
- Performing EDA (sentiment distribution, text length analysis, sample headlines).
- Running **baseline predictions** using pretrained FinBERT.
- Evaluating model performance on accuracy, F1-score, precision, and recall.
- Hyperparameter tuning and fine-tuning using **Optuna**.
- Predicting sentiment for new financial news headlines.

---

## 📂 Dataset

- The dataset used is `financial_news_sentiment_1000_clean.csv` with the following columns:
  - `headline`: Financial news headline (text)
  - `sentiment`: Label (negative, neutral, positive)
  - `label`: Numeric encoding of sentiment (0=negative, 1=neutral, 2=positive)

**Sample:**
| headline | sentiment |
|----------|-----------|
| Tech stocks rally as market sentiment improves | positive |
| Oil prices drop due to weakening global demand | negative |

> You can add your own dataset in the same format.

---

## 🛠 Project Structure

