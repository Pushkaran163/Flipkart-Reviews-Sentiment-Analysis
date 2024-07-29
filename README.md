# Flipkart-Reviews-Sentiment-Analysis

This repository contains a machine learning project for sentiment analysis on Flipkart product reviews. The project utilizes Natural Language Processing (NLP) techniques to preprocess text data and applies a Decision Tree Classifier to predict the sentiment of the reviews.

## Project Overview
The goal of this project is to classify Flipkart reviews into positive or negative sentiments based on their ratings. The dataset includes product reviews and their corresponding ratings. Positive reviews are labeled as 1 and negative reviews are labeled as 0.

## Dataset
The dataset used in this project is flipkart_data.csv. The CSV file includes the following columns:

- review: The text of the review.
- rating: The rating given by the user (1 to 5).

## Project Steps

1. Data Loading: The dataset is loaded into a Pandas DataFrame.
2. Data Exploration: Initial exploration to understand the distribution of ratings.
3. Preprocessing:
- Cleaning text data by removing punctuations and converting to lowercase.
- Removing stopwords.
4. Feature Extraction:
- Using TF-IDF Vectorization to convert text data into numerical features.
5. Model Training:
- Splitting the data into training and test sets.
- Training a Decision Tree Classifier on the training data.
6. Model Evaluation:
- Evaluating the model using accuracy score, confusion matrix, and classification report.
