## **Hepatitis-C Classification Prediction**

## **Project Overview**

Hepatitis-C Classification Prediction aims to classify liver fibrosis stages using healthcare data. The dataset is from the UCI Machine Learning Repository and contains 614 records with 14 attributes.

## **Dataset Description**

- **Source**: UCI Machine Learning Repository
- **Attributes**:
  - **Category**: Blood Donor (0), Suspect Blood Donor (0s), Hepatitis (1), Fibrosis (2), Cirrhosis (3)
  - **Demographics**: Gender, Age
  - **Lab Tests**: ALB, ALP, ALT, AST, BIL, CHE, CHOL, CREA, GGT, PROT

## **Problem Definition**

Predict liver fibrosis stages using supervised machine learning models to aid in early diagnosis and treatment.

## **Data Preprocessing**

- **Null Value Handling**: Forward filling and imputation.
- **Encoding**: Gender encoded (M=1, F=0).
- **Outlier Detection**: Analyzed via density and scatter plots.
- **Feature Engineering**: Correlation matrix to remove redundant features.

## **Models Implemented**

- Logistic Regression (Selected Model)**
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors
- Support Vector Machine
- Multi-Layer Perceptron (Neural Network)

## **Model Evaluation Metrics**

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve (AUC Score)

##**Model Selection**

- Logistic Regression was chosen for its superior performance.
  - **Highest Accuracy**: Outperformed others across key metrics.
  - **Robustness**: Effective with linear relationships and fewer outliers.

##**Authors**

  - **Aditya Gorakh Velapurkar** - velapurkar.a@northeastern.edu
  - **Sahil Sushil Mahajan** - mahajan.sah@northeastern.edu

