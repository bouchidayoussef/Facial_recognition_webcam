
# README for Youtube Comments Spam Detection Project

---

## Introduction
This project focuses on detecting spam comments from YouTube videos. The goal is to classify comments as spam or legitimate using various machine learning models.

## Dataset
The dataset used is named 'Youtube01-Psy.csv' and contains columns indicating the content of comments and their classifications (spam or not).

## Data Preprocessing
The comments underwent several preprocessing steps:
- Conversion to lowercase.
- Removal of URLs, digits, and punctuation.
- Removal of extra whitespace.

## Feature Engineering
- Vectorized the comments using the `CountVectorizer`.
- Label encoded the 'CLASS' column.

## Model Training and Evaluation
Several machine learning models were trained and evaluated on the dataset:

1. **Logistic Regression**: Evaluated based on accuracy, precision, recall, and F1 score.
2. **Support Vector Machine (SVM)**: Evaluated using similar metrics.
3. **Decision Tree**: Evaluated based on the metrics mentioned above.
4. **Random Forest**: Trained with 100 estimators.
5. **Gradient Boosting**: Trained with 100 estimators.
6. **XGBoost**: Trained with 100 estimators.

---

