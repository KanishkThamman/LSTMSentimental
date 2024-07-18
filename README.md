
# Sentiment Analysis of Twitter Data using LSTM

This project aims to perform sentiment analysis on Twitter data using a Long Short-Term Memory (LSTM) neural network. The dataset used for this project is the "Twitter Entity Sentiment Analysis" dataset available on Kaggle.

## Table of Contents
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Graphs](#graphs)
    - [LSTM Model Accuracy Over-Time](#lstm-model-accuracy-over-time)
    - [LSTM Model Loss Over-Time](#lstm-model-loss-over-time)
- [Future Work](#future-work)

## Project Overview

The project involves the following steps:

1. **Data Preprocessing:** Cleaning and preparing the Twitter data for analysis, including removing noise, handling missing values, and tokenizing the text.
2. **Model Building:** Constructing an LSTM model with appropriate layers and hyperparameters for sentiment classification.
3. **Model Training:** Training the LSTM model on the preprocessed Twitter data.
4. **Model Evaluation:** Evaluating the performance of the trained model using metrics such as accuracy, precision, and recall.

## Dependencies

The following libraries are required to run this project:

- pandas
- nltk
- scikit-learn
- TensorFlow
- Keras

## Usage

1. Download the "Twitter Entity Sentiment Analysis" dataset from Kaggle.
2. Install the required dependencies.
3. Run the provided Python code to preprocess the data, build, train, and evaluate the LSTM model.

## Results

The trained LSTM model achieves a test accuracy of %82.8, precision of 66.8, and recall of 92.1.

## Graphs

### LSTM Model Accuracy Over-Time
![Image](Images/LSTM%20ACC.png)

### LSTM Model Loss Over-TIme
![Image](Images/LSTM%20LOSS.png)


## Future Work

Possible future improvements for this project include:

- Experimenting with different model architectures and hyperparameters.
- Incorporating additional features, such as user demographics or tweet metadata.
- Deploying the trained model for real-time sentiment analysis of Twitter data.