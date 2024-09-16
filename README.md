# Rapid Classification of Emergency Events from Twitter Data
This repository contains the code and resources for the Rapid Classification of Emergency Events from Twitter Data project.
The goal of this project is to classify tweets into emergency and non-emergency categories using machine learning techniques to improve real-time event detection for emergency services.

### Table of Contents
Introduction
Dataset
Project Workflow
Modeling
Results
Technologies Used

## Introduction
In emergency situations, immediate access to accurate information can save lives. Social media platforms like Twitter serve as real-time data sources,
where users share information about ongoing events. This project aims to classify tweets related to emergency situations using Natural Language Processing (NLP) techniques.

## Dataset
We used a dataset of tweets that were manually labeled as emergency or non-emergency. Each tweet contains:
Text: The content of the tweet.
Label: A binary label (0 for non-emergency, 1 for emergency).

## Project Workflow

### Data Preprocessing:

Cleaning and preprocessing tweets by removing special characters, stopwords, and performing tokenization.
Converting text data into numerical formats using techniques like TF-IDF or Word Embeddings.
Feature Engineering:

Applying feature extraction methods like n-grams, Bag of Words, and TF-IDF to convert textual data into numerical features for model input.
Modeling:

Training machine learning models to classify tweets into emergency and non-emergency categories.

Algorithms used:
Naïve Bayes
K-Nearest Neighbors (KNN)
Ensemble Learning (Random Forest, Gradient Boosting)
Model Evaluation:

Models are evaluated using metrics like accuracy, precision, recall, and F1-score to ensure effective classification.

### Results
The best model achieved an accuracy of XX%, with a precision of YY%, recall of ZZ%, and an F1-score of AA% for emergency tweet classification.
The classification system showed significant improvement in real-time event detection.

### Technologies Used
Python: Programming language for building the project.

Libraries:
numpy, pandas: Data manipulation and analysis.
scikit-learn: Machine learning algorithms.
nltk: Natural Language Processing toolkit.
matplotlib, seaborn: Visualization libraries.
