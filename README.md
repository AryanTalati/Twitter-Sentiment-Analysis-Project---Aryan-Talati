# Twitter-Sentiment-Analysis-Project---Aryan-Talati


# Twitter Sentiment Analysis

A comprehensive sentiment analysis pipeline built on 1.6 million labeled tweets, benchmarking six machine learning and deep learning models to classify tweet sentiment as positive, negative, or neutral.

## Overview

This project explores how well different ML architectures handle real-world social media text — including noisy language, slang, and sarcasm. The pipeline covers everything from data preprocessing and feature engineering to model training, evaluation, and trend extraction.

## Results

| Model | Accuracy / Score |
|---|---|
| CNN | **97.85%** |
| BERT | **0.91 F1-score** |
| SVM | 85% |
| LSTM | 85% |
| Logistic Regression | Baseline |
| Naïve Bayes | Baseline |

- BERT outperformed traditional models on nuanced language like sarcasm, improving detection from an 80% baseline to **91% accuracy**
- CNN achieved the highest raw accuracy at **97.85%**
- Extracted actionable trends including **evening spikes in negative sentiment**

## Tech Stack

- **Languages:** Python
- **ML/DL:** TensorFlow, Keras, Scikit-Learn
- **Models:** BERT, CNN, LSTM, SVM, Logistic Regression, Naïve Bayes
- **Data Processing:** pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Google Colab (GPU)

## Dataset

- 1.6 million labeled tweets with sentiment labels (positive, negative, neutral)
- Features include tweet text, time of tweet, user age group, and country-level demographic data
- Preprocessing pipeline includes tokenization, padding, and text normalization

## Key Features

- **Multi-model benchmarking** — rigorous comparison across 6 architectures on the same dataset
- **Context-aware NLP** — BERT fine-tuned for detecting nuanced sentiment including sarcasm
- **Trend analysis** — temporal sentiment patterns extracted and visualized
- **Real-time inference pipeline** — preprocessing and inference pipeline built for brand and customer monitoring use cases

## How to Run

1. Open the notebook in Google Colab
2. Mount your Google Drive and place the dataset CSV files at `/content/drive/My Drive/DM_Project_CSV/`
3. Run all cells in order
4. GPU runtime recommended for BERT training

## Course

Data Mining 572 — Arizona State University (Fall 2024)
