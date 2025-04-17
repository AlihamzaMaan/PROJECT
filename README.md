# Sentiment Analysis: Twitter vs Amazon Review Data

## Overview
This project performs sentiment analysis on both Twitter data and Amazon review data. The notebook compares various sentiment analysis models—ranging from traditional machine learning algorithms (e.g., Logistic Regression, Naive Bayes, Random Forest, Linear SVC) to deep learning methods (LSTM, GRU). Techniques for handling imbalanced data (SMOTE, SMOTENC, ADASYN, etc.) are used extensively.

## Requirements
- Python 3.12
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imblearn, nltk, tensorflow, keras, and others as required.

## Project Structure
- **Data Loading & Preprocessing**: Load CSV and TXT datasets, clean the text, handle missing values, and apply various preprocessing steps.
- **Feature Engineering**: Generate text embeddings using CountVectorizer.
- **Modeling**: Build and evaluate multiple models including traditional ML classifiers, LSTM and GRU networks for deep learning.
- **Evaluation**: Compare model performance using metrics (accuracy, precision, recall, F1, ROC), confusion matrices, and ROC curves.
- **Twitter Sentiment Analysis**: Analyze sentiment on tweets using Tweepy and TextBlob (detailed in a separate section).

## Model Details & Results
- **Traditional ML Models**: Logistic Regression with various resampling techniques, Multinomial Naive Bayes, Random Forest, and Linear SVC.
- **Deep Learning Models**: LSTM and GRU architectures are implemented to assess performance on sequential data.
- **Visualization**: Comparisons of model accuracies and confusion matrices are generated to assist in model selection.
