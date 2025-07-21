# Sentiment-Analysis-on-Amazon-Fine-Food-Reviews

The uploaded code includes model implementations and feature engineering workflows based on both TF-IDF and Word2Vec representations.

# Project Overview

This project performs sentiment analysis on the Amazon Fine Food Reviews dataset using a combination of traditional machine learning, deep learning, and transformer-based models. The objective is to classify reviews as Positive, Neutral, or Negative, leveraging various NLP techniques and web mining methods to analyze large-scale consumer feedback.

# Dataset

- Source: [Kaggle - Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data)

- Size: ~568,000 reviews spanning over 10 years

- Features used: Review Text, Summary, and Score

# Sentiment Mapping:

- Positive (Score > 3)

- Neutral (Score = 3)

- Negative (Score < 3)

# Preprocessing Steps

- Removed null values and duplicates

- Cleaned HTML tags and punctuations

- Stopwords filtered with negations preserved

- Handled class imbalance using sampling techniques

- Data split into 80:20 train-test sets

# Feature Engineering

- TF-IDF

- Word2Vec embeddings

# Models Implemented

- Logistic Regression (baseline)

- Naive Bayes

- Random Forest

- Support Vector Machines (SVM)

- LSTM (deep learning)

- Transformer Models: BERT, RoBERTa, DistilBERT

# Key Findings

DistilBERT delivered the best overall performance, especially on positive and neutral sentiments

TF-IDF worked best with traditional models, while LSTM and transformers benefitted from dense embeddings

Class balancing significantly impacted model performance

# Future Scope

- Explore ensemble models

- Advanced fine-tuning of transformer models

- Experiment with sentiment lexicons

# Contributors

- Sushma Kulkarni

- Krittika Sardar

- Mansi Sawant

- Nishit Suthar

- Eljes Basha
