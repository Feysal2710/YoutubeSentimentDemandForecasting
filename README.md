# YoutubeSentimentDemandForecasting
YouTube Comments Sentiment analysis &amp; Demand forecasting Automotive Industry in the Netherlands. Keep in mind when opening the files check which step it is e.g. step 1 or step 2, which you can find at the end of the title of the files.
#  Keep in mind when opening the files check which step it is e.g. step 1 or step 2, which you can find at the end of the title of the files.

**Thesis Project: YouTube Comments Sentiment Analysis & Demand Forecasting for the Automotive Industry in the Netherlands**

---

## Overview

This project is part of a university thesis exploring how sentiment extracted from YouTube car review comments can support **demand forecasting** in the automotive sector.

It involves:
- Collecting and cleaning multilingual YouTube comments
- Manually annotating sentiment labels (Negative, Neutral, Positive)
- Training and evaluating various machine learning and deep learning models
- Applying the best sentiment models to unlabeled YouTube data
- Preparing sentiment time-series data for future demand forecasting (not yet in this repo)

---

## Models Implemented (with highest scores on language (or combined))

| Model                        | Language    | Best Accuracy |
|-----------------------------|-------------|---------------|
| BERT (Zero-shot, Roberta)   | English     | 83.4%         |
| BERT (Fine-tuned)           | Combined    | 73.1%         |
| Logistic Regression         | Dutch       | 61.0%         |
| CNN (Fine-tuned)            | Combined    | 56.4%         |
| LSTM (FastText)             | English     | 57.3%         |
| LSTM (FastText)             | Dutch       | 53.1%         |

Models were trained on **manually labeled comments** in both English and Dutch, and validated using traditional metrics (accuracy, macro F1, confusion matrix).

---

## 📁 Project Structure

