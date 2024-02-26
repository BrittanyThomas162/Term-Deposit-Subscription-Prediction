# Binary Classification for Term Deposit Subscription Prediction

## Overview:

This project focuses on utilizing machine learning algorithms to predict whether clients of a banking institution will subscribe to a term deposit, based on data obtained from direct marketing campaigns. 

The training dataset comprises various features, including:

  **Client demographics**: Age, job, marital status, education
  Financial information: Balance, default status, housing loan, personal loan
  Contact details: Contact type, communication month, last campaign outcome
  **Marketing Campaign Data**: Number of times contacted, number of days since   the last contact, previous campaign outcome
  **Target variable**: Indicates whether the client subscribed to a term   
    deposit (Yes/No)

## Methodology:

**1. Data Exploration and Analysis**:

Utilized **Pandas** for data manipulation and exploration.
Investigated the dataset's structure, checked for missing values, and examined summary statistics.
Employed **Matplotlib** for visualizing distributions, correlations, and other patterns in the data.

**2. Feature Engineering**:

Examined categorical variables and applied Label Encoding to convert them into numerical format.
Conducted feature selection using **SelectKBest** to identify the most relevant features for model training.

**3. Data Preprocessing**:

Standardized numerical features using **StandardScaler** to ensure they have a mean of 0 and standard deviation of 1.
Split the dataset into training and testing sets using train_test_split for model evaluation.

**4. Model Development**:

Implement various machine learning algorithms suitable for *binary classification* tasks, such as:

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest
- Multi-Layer Perceptron (MLP)
- TensorFlow Neural Network

Train each model using the preprocessed data and evaluate their performance.

**5. Model Evaluation**:

Assess the performance of each model using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score
- Area Under the ROC Curve (AUC)

Compare the models to identify the one with the best performance for predicting term deposit subscriptions.

**6. Prediction and Deployment**:

Use the best-performing models to make predictions on new data or unseen instances.
