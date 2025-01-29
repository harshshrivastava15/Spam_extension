# Spam Detection Model

This project implements a machine learning model for spam email detection using Natural Language Processing (NLP). It uses a dataset of messages labeled as spam or ham (non-spam) to train the model and predict whether a given message is spam or not.

## Features

- **Dataset**: The dataset used in this project contains labeled messages classified as either "spam" or "ham". 
- **Machine Learning Model**: A Naive Bayes classifier is trained to classify the messages based on their content.
- **Text Vectorization**: `CountVectorizer` is used to convert text into numerical feature vectors.
- **Model Evaluation**: The model is evaluated using metrics like accuracy, confusion matrix, and classification report.
- **SVM Model**: An optional Support Vector Machine (SVM) model is trained as an alternative.
- **Pickle Export**: The trained model and vectorizer are saved as `.pkl` files for future use and inference.

## Installation

Clone this repository to your local machine and install the necessary dependencies:

```bash
git clone https://github.com/harshshrivastava15/spam-detection.git
cd spam-detection
