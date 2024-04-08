# M13
# Spam Email Classification Project

## Overview
This project aims to classify emails as spam or not spam using machine learning algorithms. The dataset used for this project contains various features extracted from emails, such as word frequency, character frequency, and capital run length statistics. We train logistic regression and random forest classifier models on the dataset and evaluate their performance using accuracy scores.

## Dataset
The dataset used in this project can be found [here](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv). It contains the following columns:

- `word_freq_make`: Frequency of the word "make" in the email
- `word_freq_address`: Frequency of the word "address" in the email
- ...
- `capital_run_length_total`: Total length of uninterrupted sequences of capital letters
- `spam`: Binary label indicating whether the email is spam (1) or not spam (0)

## Steps

1. **Importing Libraries:** We import necessary libraries such as pandas, scikit-learn, and matplotlib.

2. **Data Loading:** The dataset is loaded into a pandas DataFrame.

3. **Data Exploration:** We explore the dataset by examining its structure and summary statistics.

4. **Data Preprocessing:** We split the dataset into features (X) and labels (y) and then split it into training and testing sets.

5. **Feature Scaling:** We scale the features using the StandardScaler to ensure that they have similar scales.

6. **Model Training:** We train logistic regression and random forest classifier models on the training data.

7. **Model Evaluation:** We make predictions using the trained models on the testing data and evaluate their performance using accuracy scores.

## Results
- Logistic Regression Model Accuracy: 0.95
- Random Forest Classifier Model Accuracy: 0.97

## Conclusion
Both logistic regression and random forest classifier models achieved high accuracy in classifying spam emails. The random forest classifier slightly outperformed the logistic regression model. Further optimization and tuning of hyperparameters may improve the performance of these models.

## Sources
Python (or any other programming language of choice) Command-line interface (CLI) or Graphical user interface (GUI) based on the application design Contribution Code used in this project was referenced from prior modules, ChatGPT, Copilot, and various Google searches to help understand syntax and correct errors.
