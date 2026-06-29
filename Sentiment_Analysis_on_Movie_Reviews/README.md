# Sentiment Analysis on Movie Reviews

## Overview

This project aims to classify movie reviews as Positive or Negative using Natural Language Processing (NLP) and Machine Learning algorithms. Text preprocessing techniques and TF-IDF vectorization were applied to convert raw movie reviews into numerical features before training multiple classification models.

## Dataset

This project uses the IMDB Dataset of 50K Movie Reviews from Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Download the dataset and place IMDB Dataset.csv in the project root directory before running the notebook.

## Algorithms Used

- Naive Bayes Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## Project Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis
4. Label Encoding
5. Text Cleaning
6. Stopword Removal
7. Stemming
8. TF-IDF Vectorization
9. Train-Test Split
10. Model Training
11. Model Evaluation
12. Accuracy Comparison

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 88.64% |
| XGBoost | 86.02% |
| Naive Bayes | 85.14% |
| Random Forest | 84.85% |
| K-Nearest Neighbors (KNN) | 76.13% |
| Decision Tree | 72.15% |

## Conclusion

Among all the machine learning models, Logistic Regression achieved the highest accuracy of **88.64%** and performed best for sentiment classification on the IMDB movie reviews dataset. The project demonstrates the effectiveness of TF-IDF vectorization combined with traditional machine learning algorithms for Natural Language Processing (NLP) tasks.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- NLTK
- XGBoost
