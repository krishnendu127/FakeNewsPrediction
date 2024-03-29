# Fake News Detection

## Overview
This project aims to detect fake news articles using machine learning techniques. It utilizes a logistic regression model trained on a dataset containing labeled news articles to classify whether a given news article is real or fake. The model preprocesses the textual data, applies stemming, and converts it into numerical features using TF-IDF vectorization.

## Dataset
The dataset used for training the model is sourced from '/content/train.csv'. It contains news articles along with their labels, where:
- 1 indicates a fake news article
- 0 indicates a real news article

## Features
- **Data Preprocessing**: Null value handling, merging author and news title, text cleaning, and stemming.
- **Feature Extraction**: Conversion of textual data into numerical features using TF-IDF vectorization.
- **Model Training**: Utilization of logistic regression for classification.
- **Model Evaluation**: Assessment of model performance using accuracy metrics on both training and testing data.
- **Prediction**: Deployment of the trained model to classify new news articles.

## Dependencies
- NumPy
- Pandas
- NLTK (Natural Language Toolkit)
- Scikit-learn

## Usage
1. Ensure you have the necessary dependencies installed.
2. Download the dataset from the provided link and place it in the correct directory.
3. Run the code in a Python environment such as Jupyter Notebook or Google Colab.
4. The code will preprocess the data, train the model, evaluate its performance, and make predictions on new data.
5. You can modify the code or experiment with different machine learning algorithms for further improvements.
