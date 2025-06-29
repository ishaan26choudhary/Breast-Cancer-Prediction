# Breast-Cancer-Prediction
## Overview
This project implements a machine learning pipeline to predict breast cancer outcomes using Logistic Regression. The dataset consists of medical diagnostic features, and the goal is to classify tumors as malignant or benign.

## Dataset
The dataset used is `breast_cancer.csv`. It contains 683 records with the following columns:

- `Sample code number`: Unique Identifier (not used for prediction)
- `Clump Thickness`
- `Uniformity of Cell Size`
- `Uniformity of Cell Shape`
- `Marginal Adhesion`
- `Single Epithelial Cell Size`
- `Bare Nuclei`
- `Bland Chromatin`
- `Normal Nucleoli`
- `Mitoses`
- `Class`: Target label (`2` = Benign, `4` = Malignant)

## Steps Performed
1. **Import Libraries:** Utilizes Python's popular libraries - NumPy, Pandas, Scikit-learn.
2. **Load Dataset:** Reads the dataset and extracts feature variables (`X`) and target labels (`y`). The identifier column is excluded.
3. **Data Splitting:** Splits data into training and testing sets using an 80:20 ratio.
4. **Model Training:** Trains a Logistic Regression classifier on the training set.
5. **Prediction:** Uses the trained model to predict outcomes on the test set.
6. *(Optional steps like evaluation, accuracy measurement, or confusion matrix visualization can be added.)*

## Requirements
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
