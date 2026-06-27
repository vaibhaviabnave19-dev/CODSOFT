# Task2: SMS Spam Classification

## Objective
Build an AI model that can classify SMS messages as **spam** or **legitimate** using Natural Language Processing (NLP) techniques.

## Description
This project applies text preprocessing and feature extraction methods such as **TF-IDF vectorization** or **word embeddings**. The extracted features are then used to train machine learning classifiers to detect spam messages.

## Models Used
1. Logistic Regression
2. Naive Bayes
3. Support Vector Machine (SVM)

## Workflow
1. Data Collection: Use a labeled SMS dataset (spam vs. ham).
2. Data Preprocessing: Clean text (remove punctuation, stopwords, lowercase).
3. Feature Extraction: Apply TF-IDF or word embeddings to convert text into numerical vectors.
4. Model Training: Train classifiers (Naive Bayes, Logistic Regression, SVM).
5. Model Evaluation: Compare models using accuracy, precision, recall, and F1-score.
6. Model Selection: Choose the best performing model for deployment.

## Result
The selected Naive Bayes model achieves high accuracy in distinguishing spam from legitimate SMS messages. It can be used to automatically filter unwanted spam messages in real-world applications.
