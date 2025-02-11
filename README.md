# Financial-Sentiment-Analysis

# Sentiment Analysis of Financial News Articles

## Overview
This repository contains code and resources for classifying financial news articles into positive and negative sentiments. The project compares the performance of neural network (CNN) and boosting (XGBoost) models for accurate classification.

## Objective
- Classify financial news articles based on sentiment.
- Distinguish between positive and negative sentiments.
- Compare neural network and boosting models to determine the most effective approach.

## Dataset
- **Source**: Collection of financial news articles.
- **Columns**: `Sentiment`, `Sentence`.
- **Total Samples**: ~2000 articles.
- **Preprocessing**: Cleaning, tokenization, and encoding.

## Methodology
1. **Data Cleaning and Preprocessing**
   - Standard cleaning techniques.
   - Tokenization and TF-IDF for feature extraction.

2. **Handling Class Imbalance**
   - Applied oversampling techniques to balance the dataset.

3. **Model Building**
   - **CNN**: Built using Keras with tuned dropout rates.
   - **XGBoost**: Implemented with optimized parameters.
   - **Random Forest**: Used as a baseline with hyperparameter tuning.

4. **Hyperparameter Tuning**
   - **CNN**: Tuned using Keras-Tuner's RandomSearch.
   - **XGBoost**: Optimized with RandomizedSearchCV for parameters like learning rate, max-depth, and n_estimators.
   - **Random Forest**: Tuned for n_estimators, max_depth, etc.

5. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1 Score, AUC.

## Results
- Achieved **80%+ accuracy** in sentiment classification.
- **XGBoost** marginally outperformed CNN.
- Effective hyperparameter tuning significantly enhanced model performance.
- Additional tuning for CNN could improve its performance further.

## Novelties of the Approach
- Combined deep learning (CNN) with traditional ML models (XGBoost, Random Forest).
- Implemented advanced hyperparameter tuning techniques.
- Comprehensive evaluation metrics applied to assess model robustness.
- Addressed class imbalance effectively to improve classification accuracy.



