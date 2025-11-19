Logistic Regression Classification Project
📌 Project Title: Binary Classification using Logistic Regression

This project demonstrates how to build a binary classification model using Logistic Regression.
The project includes data preprocessing, model training, evaluation using multiple metrics, ROC-AUC analysis, and threshold tuning.

📁 Dataset

The dataset used in this project is:

📂 data.csv (uploaded by the user)

To load the dataset:

df = pd.read_csv("/mnt/data/data.csv")


You must set the correct target column before training.

🎯 Objective

Build and evaluate a binary classifier using Logistic Regression with the following steps:

Load and explore the dataset

Clean and preprocess data

Split into train/test sets

Standardize features

Train a Logistic Regression model

Evaluate performance

Plot ROC curve

Tune classification threshold

Explain sigmoid function

🛠 Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

📌 Steps Performed
1. Load Dataset

The uploaded CSV file is loaded using Pandas.

2. Data Preprocessing

Handle missing values

Encode target variable

Select features and label

3. Train/Test Split

Dataset is split into:

80% Training data

20% Testing data

4. Feature Scaling

StandardScaler is used to normalize input features.

5. Logistic Regression Model

A logistic regression classifier is trained using:

model = LogisticRegression(max_iter=500)

6. Model Evaluation

The following metrics are calculated:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Confusion Matrix

7. ROC Curve

A Receiver Operating Characteristic (ROC) curve is plotted to measure performance across thresholds.

8. Threshold Tuning

Default threshold (0.5) is adjusted to improve Recall or Precision depending on use-case.

9. Sigmoid Function


	​


It converts linear output into probability.

📊 Model Performance Metrics

After training, the following metrics are displayed:

Confusion matrix

Precision, Recall, F1

ROC-AUC score

ROC curve visualization

📁 Project Structure
├── data.csv               # Dataset (uploaded)
├── logistic_regression.py # Main classification script
├── README.md              # Project documentation

▶️ How to Run the Project

Install the dependencies:

pip install pandas numpy scikit-learn matplotlib


Run the main script:

python logistic_regression.py


The ROC curve will appear as a pop-up window.

📌 What You Will Learn

Binary classification

Logistic Regression working principle

Importance of scaling

How sigmoid converts outputs to probabilities

Evaluation metrics

ROC curve & AUC

Threshold tuning
