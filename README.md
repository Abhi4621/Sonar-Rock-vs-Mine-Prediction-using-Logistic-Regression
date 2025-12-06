# Sonar Rock vs Mine Classification

This project uses Logistic Regression to classify sonar signals as either **Rock (R)** or **Mine (M)**.  
The dataset contains 208 samples with 60 numerical features representing sonar frequency readings.

## Features
- Load and explore the dataset
- Data preprocessing and label separation
- Train-test split (90-10 ratio)
- Logistic Regression model training
- Accuracy evaluation

## Requirements
- Python 3.x
- NumPy
- Pandas
- scikit-learn

Install dependencies:
pip install numpy pandas scikit-learn
How to Run

Place the dataset file (sonar data.csv) in your working directory.

Run the Python script or Jupyter Notebook.

The model will train and display accuracy scores for both training and test sets.

Dataset

The dataset consists of:

60 numerical features

1 label column (R = Rock, M = Mine)
Source: UCI Machine Learning Repository.

Output

The script prints:

Shape of dataset

Statistical summary

Accuracy of the logistic regression classifier
