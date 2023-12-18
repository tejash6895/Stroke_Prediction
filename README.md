# Stroke Prediction Analysis

## Overview
This project focuses on predicting strokes using a dataset that includes various patient features. The core of the analysis is built using logistic regression. We employ techniques like data preprocessing, one-hot encoding, SMOTE for handling imbalanced datasets, and GridSearchCV for hyperparameter tuning.

## Dataset
The dataset used in this project is for stroke prediction and includes features like age, gender, BMI, and smoking status. It is divided into a training set and a test set.

## Features
- **Data Preprocessing**: Handling missing values and encoding categorical variables.
- **Feature Scaling**: Application of MinMaxScaler for normalizing feature values.
- **SMOTE**: Synthetic Minority Over-sampling Technique to address class imbalance.
- **Model Training and Evaluation**: Logistic Regression with hyperparameter tuning using GridSearchCV.
- **Prediction**: Making predictions on test data and preparing a submission file.

## Requirements
To run this code, you need the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `imblearn`
- `matplotlib`
- `seaborn`

## Installation
You can install the required packages using pip:
```bash
pip install numpy pandas scikit-learn imbalanced-learn matplotlib seaborn

## Usage
- Clone this repository.
- Place the stroke dataset in the appropriate directory (as per the code's file paths).
- Run the Jupyter Notebook or Python script.

##Files in the Repository

- stroke_prediction.ipynb: Jupyter Notebook containing the analysis and model training.
- stroke_train_set.csv: Training dataset for the model.
- stroke_test_set_nogt.csv: Test dataset for making predictions.
- submission.csv: Output file with predictions.


## License
Distributed under the MIT License. See LICENSE for more information.
