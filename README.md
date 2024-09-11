# E-commerce-Product-Categorization
SmartSort: E-commerce Product Categorization with Machine Learning

## Overview

SmartSort is a sophisticated machine learning project designed to accurately classify e-commerce product descriptions into predefined categories using state-of-the-art NLP techniques and machine learning algorithms. Leveraging pre-trained Word2Vec embeddings alongside TF-IDF, this project enhances text representation to improve model performance. With baseline models, including XGBoost, Linear SVM, and Logistic Regression, the project fine-tunes hyperparameters to achieve optimal accuracy, ultimately assisting businesses in automating product classification for improved searchability and user experience.

## Key Features

Word Embeddings Integration: Utilizes Google’s pre-trained Word2Vec embeddings for context-rich product descriptions.

TF-IDF Representation: Employs traditional Term Frequency-Inverse Document Frequency (TF-IDF) alongside Word2Vec for comprehensive text representation.

Baseline Modeling & Hyperparameter Tuning: Experiments with various classifiers, including XGBoost, SVM, Random Forest, and more, fine-tuning hyperparameters for the best performance.

Data Preprocessing: Partial text normalization, handling contractions, and tokenization to prepare raw product descriptions for embedding.

Model Evaluation: Compares classifiers' performance based on training, validation, and test accuracy, using confusion matrices for detailed evaluation.


In this project, we aimed to classify e-commerce products into four distinct categories—Electronics, Household, Books, and Clothing & Accessories—based on their descriptions. After a comprehensive exploratory data analysis and application of various text normalization techniques, we utilized both TF-IDF vectorization and Word2Vec embeddings to transform the product descriptions into numerical representations.

The comparative analysis of classifiers, coupled with hyperparameter tuning, revealed that the XGBoost model performed exceptionally well with the highest validation accuracy. By leveraging advanced vectorization techniques and optimizing model parameters, we achieved a remarkable test accuracy of 94.89%. This demonstrates the effectiveness of our approach in accurately categorizing e-commerce products and showcases the potential of combining different text processing and machine learning strategies to solve real-world classification problems.


