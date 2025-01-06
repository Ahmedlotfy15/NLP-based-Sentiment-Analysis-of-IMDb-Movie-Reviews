# Sentiment Analysis on IMDb Movie Reviews

This repository contains a project for sentiment analysis on IMDb movie reviews using machine learning techniques. The analysis involves cleaning and preprocessing the data, extracting features, training a model, and evaluating its performance.

## Project Overview

1. **Data Cleaning**:
   - Removed stopwords and applied lemmatization using spaCy to standardize text.
   
2. **Feature Extraction**:
   - Used TF-IDF Vectorizer with n-grams (unigrams and bigrams) for better feature representation.

3. **Model Training**:
   - Trained a Logistic Regression model and optimized its hyperparameters using GridSearchCV.

4. **Evaluation**:
   - Evaluated the model with metrics such as accuracy, confusion matrix, and classification report.
   - Used Cross Validation for robust performance evaluation.

5. **Visualization**:
   - Generated a WordCloud to visualize the most frequent words in the reviews.

---
