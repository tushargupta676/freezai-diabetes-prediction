# FreezAI Diabetes Prediction

## Overview

This project was developed as part of the **FreezAI Kaggle-style Machine Learning Competition** organized by Geek Room. The objective was to predict whether an individual is likely to have diabetes based on health-related attributes provided in the dataset.

## Problem Statement

Predict the **Outcome** for each individual in the test dataset.

This is a binary classification task where the model determines whether a person is likely to have diabetes using the given medical and demographic features.

## Dataset

The dataset consists of:

- **train.csv** – Training dataset containing input features and the target variable (**Outcome**)
- **test.csv** – Test dataset used for generating predictions
- **sample_submission.csv** – Sample file showing the required submission format

## Approach

The project follows a standard Machine Learning workflow:

1. Data Loading and Exploration
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Understanding
5. Model Training using Random Forest Classifier
6. Model Evaluation
7. Prediction Generation
8. Competition Submission

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

## Model Used

### Random Forest Classifier

A Random Forest model was trained on the processed training data to classify whether an individual is diabetic or non-diabetic. The model combines multiple decision trees to improve prediction accuracy and reduce overfitting.

## Results

The trained model was used to generate predictions for the competition test dataset and create the final submission file.

**Competition Private Score:** 0.71966

## Repository Structure

```text
freezai-diabetes-prediction/
│
├── README.md
├── freezai_diabetes_prediction.ipynb
├── submission.csv
│
└── data/
    ├── train.csv
    ├── test.csv
    └── sample_submission.csv
```

## Learning Outcomes

- Data preprocessing using Pandas
- Exploratory Data Analysis (EDA)
- Feature engineering and feature understanding
- Building classification models using Scikit-Learn
- Applying Random Forest for binary classification
- Generating predictions for Kaggle-style competition submissions

## Author

**Tushar Gupta**

B.Tech Information Technology (2024–2028)

