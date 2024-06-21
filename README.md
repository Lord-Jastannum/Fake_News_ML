Fake News Detection Using Machine Learning

Drawing from two distinct datasets sourced from Kaggle—one containing fake news and the other comprising genuine news—we navigate through the complex landscape of data preprocessing and feature engineering. With the aid of TF-IDF to unravel word weightage and regex functions to refine our dataset, we lay a solid foundation for our predictive model.

Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Shuffling](#shuffling)
- [Cleaning](#cleaning)
- [Training](#training)
  - [Logistic Regression](#logistic-regression)
  - [Decision Tree Classifier](#decision-tree-classification)
  - [Random Forest Classifier](#random-forest-classifier)

Introduction
Fake news is a major problem in today's digital age. It can spread misinformation and create confusion among people. This project uses a machine learning approach to classify news articles as fake or real using various classification algorithms and TF-IDF for feature extraction.

Datasets
The dataset used in this project is the "Fake and Real News Dataset" available on Kaggle. It consists of two CSV files:
- `Fake.csv`: Contains fake news articles.
- `True.csv`: Contains real news articles.
You can download the dataset from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset).
The CSV files have also be included in the repository

Shuffling
To ensure that the model does not learn any ordering or position biases from the dataset, we shuffle the dataset before splitting it into training and test sets.

Cleaning
Data cleaning involves removing non-word characters, extra spaces, converting text to lowercase, and removing stopwords. Lemmatization is also applied to reduce words to their base form.

Training
We use TF-IDF to convert the text data into numerical features and then apply various classification algorithms.

Logistic Regression
Logistic Regression is a simple and effective linear model for binary classification.
Decision Tree Classifier
A Decision Tree Classifier is a non-linear model that splits the data based on feature values to make predictions.
Random Forest Classifier
Random Forest is an ensemble method that uses multiple decision trees to improve performance and reduce overfitting.

