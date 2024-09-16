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
We used a dataset of tweets that were manually labeled as emergency or non-emergency.

Train dataset:
Number of rows(tweets) : 7613
Each tweet contains:
Text: The content of the tweet.
Label: A binary label (0 for non-emergency, 1 for emergency).

Class % in train dataser: 
disaster(1) --->43%
not disaster(0) --->57%

Test dataset:
Number of rows(tweets) : 3263



## Project Workflow

### Data Preprocessing:

Cleaning and preprocessing tweets by removing special characters, stopwords,html tag,emails,dates,# names,IPs,Symbols and performing tokenization.

Converting text data into numerical formats using techniques like TF-IDF or Word Embeddings.
Feature Engineering:

Applying feature extraction method TF-IDF to convert textual data into numerical features for model input.

## Modeling:
Training machine learning models to classify tweets into emergency and non-emergency categories.

Algorithms used:
Naïve Bayes
K-Nearest Neighbors (KNN)
Ensemble Learning (Random Forest)

## Model Evaluation:
Models are evaluated using metrics like accuracy, precision, recall, and F1-score to ensure effective classification.

## Results
Random Forest (Best Model)
Test Accuracy: 79.2%

Classification Report:
Precision: 0.75 (class 0), 0.92 (class 1)
Recall: 0.96 (class 0), 0.56 (class 1)
F1-Score: 0.84 (class 0), 0.70 (class 1)
The Random Forest model outperforms other models significantly, achieving the highest accuracy and providing a good balance between precision and recall for both classes.

## Technologies Used
Python: Programming language for building the project.

## Libraries:
numpy, pandas: Data manipulation and analysis.
scikit-learn: Machine learning algorithms.
nltk: Natural Language Processing toolkit.
wordcloud: to take overview of most frequenst words
matplotlib, seaborn: Visualization libraries.
