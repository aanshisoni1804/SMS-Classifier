# SMS Spam Detection using NLP and Machine Learning

This project implements a complete pipeline for detecting spam messages in SMS data using Natural Language Processing (NLP) and machine learning models. It includes data preprocessing, feature extraction using TF-IDF, and classification using Naive Bayes, Support Vector Machine (SVM), and Logistic Regression.

## Dataset
- **Name:** SMS Spam Collection
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)
- **Format:** Tab-separated values (`\t`)
- **Classes:** `ham` (non-spam), `spam`

## Key Steps

### Data Preprocessing
- Text cleaning (removing emails, URLs, numbers, special characters)
- Lowercasing
- Tokenization, stopword removal, and stemming

### Feature Extraction
- TF-IDF vectorization to convert text into numerical features

### Model Training and Evaluation
- Models trained: Naive Bayes, SVM, Logistic Regression
- Evaluation using Accuracy, Precision, Recall, F1-Score, Confusion Matrix

### Visualization
- Bar chart for class distribution
- WordClouds for most frequent words in spam and ham messages

## Model Performance

| Model                | Accuracy |
|----------------------|----------|
| Naive Bayes          | 98.0%    |
| Support Vector Machine (SVM) | 98.4%    |
| Logistic Regression  | 97.2%    |
