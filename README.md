# Amazon Reviews Sentiment Analysis

## Overview
This project compares **LSTM and BERT** models for classifying Amazon customer reviews into three sentiment categories using the `SetFit/amazon_reviews_multi_en` dataset.

## Sentiment Classes
- **0:** Negative (1-star reviews)
- **1:** Neutral (2-star reviews)
- **2:** Positive (3–5-star reviews)

## Models Used
- **LSTM:** Learns sequential patterns in review text using tokenization and padding.
- **BERT:** Uses a pre-trained transformer model, fine-tuned for sentiment classification.

## Workflow
1. Load and preprocess the dataset.
2. Select balanced samples from each sentiment class.
3. Tokenize and prepare review text.
4. Train the LSTM and BERT models.
5. Evaluate and compare accuracy, precision, recall, and F1-score.

## Technologies
Python, Pandas, TensorFlow/Keras, Hugging Face Transformers, Scikit-learn.

## Outcome
Compare both models' performance to determine which performs better on the selected test sample.
