﻿# ML_lung_cancer
 # Cancer Patient Dataset Analysis Documentation

## Introduction
This documentation provides an overview and detailed explanation of the analysis performed on the cancer patient dataset.

## Dependencies
The code requires the following dependencies:
- pandas
- matplotlib
- numpy
- seaborn
- keras
- scikit-learn

## Description
The provided code performs the following tasks:
- Imports necessary libraries.
- Loads the cancer patient dataset from a CSV file.
- Provides descriptive statistics of the dataset.
- Displays concise information about the dataset.
- Preprocesses the dataset by dropping unnecessary columns.
- Visualizes the distribution of the 'Level' variable using a pie chart.
- Encodes categorical variables in the 'Level' column.
- Generates a correlation matrix heatmap.
- Splits the dataset into training and testing sets.
- Builds and evaluates machine learning models including KNN, Naive Bayes, Logistic Regression, and Support Vector Machines.
- Normalizes the data and performs one-hot encoding for neural network training.
- Builds a neural network model using Keras.
- Trains the neural network model and evaluates its performance.
- Visualizes the accuracy and loss of the neural network model over epochs.

## Usage
To use this code:
1. Ensure all dependencies are installed.
2. Replace the file path in the `pd.read_csv()` function with the path to your dataset.
3. Run each code cell sequentially to perform the analysis.

## Example
```python
# Replace 'cancer_patient_data.csv' with the path to your dataset
df = pd.read_csv('cancer_patient_data.csv')
df.describe()
df.info()
# Continue running each code cell as needed
