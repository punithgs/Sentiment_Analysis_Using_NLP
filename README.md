# Sentiment Analysis using Natural Language Processing and Machine Learning with 96.8% Accuracy


## Table of Contents

- [Overview](#overview)
- [Project Steps](#project-steps)
- [Dataset](#dataset)
- [Models](#models)


## Overview

1. Sentiment Analysis, a subset of Natural Language Processing (NLP), is a powerful technique that aims to determine the sentiment or emotional tone expressed in a piece of text. It involves the use of advanced machine learning models and linguistic analysis to classify the sentiment as positive, negative, or neutral. In my project, I leverage Sentiment Analysis using a Random Forest Classifier, a machine learning model known for its efficiency and accuracy. **The final accuracy for my Machine Learning model was 96.8%**

2. My project focuses on sentiment analysis of textual data, a crucial task with diverse real-world applications. By accurately identifying the sentiment of social media posts, product reviews, or customer feedback, businesses can gain valuable insights into public opinion. For instance, analyzing customer reviews can help companies understand customer satisfaction, identify areas for improvement, and tailor their marketing strategies accordingly.


## Project Steps

The primary goals of this project are as follows:

1. **Text Processing**: Perform thorough text cleaning, including lowercasing, removing special characters, and handling stopwords to enhance the quality of the data.

2. **Tokenization and Lemmatization**: Utilize NLP techniques to tokenize the text into words or subwords and apply lemmatization to convert words to their base or root forms.

3. **Text Vecttorizer using Count Vectorization**: Implement Count Vectorizer to convert the preprocessed text data into numerical feature vectors, representing word counts for each document.

4. **Exploratory Data Analysis**: Conduct EDA to gain insights into the dataset, analyze the distribution of sentiment classes, and visualize patterns within the text data.

5. **Model Training with Random Forest**: Train a Random Forest Classifier on the count vectorized features obtained from NLP preprocessing, ensuring the model can effectively predict sentiment labels.

6. **Model Evaluation and Interpretability**: Evaluate the model's performance using appropriate evaluation metrics and provide insights into feature importance to enhance interpretability and understanding of the sentiment analysis.


## Technologies and Libraries Used

- Python
- NumPy
- Scikit-learn
- Pandas
- Matplotlib/Seaborn
- NLTK (For Natural Language Processing tasks)


## Dataset

I sourced my dataset from kaggle where a wide variety of datasets from various topics are available.
Link to the dataset - https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis


## Models

1. **Random Forest**: Random Forest is a versatile ensemble learning technique in machine learning. It builds multiple decision trees and aggregates their predictions to improve accuracy and mitigate overfitting, making    it widely used for classification and regression tasks. Its strength lies in combining diverse models for robust and reliable predictions.
