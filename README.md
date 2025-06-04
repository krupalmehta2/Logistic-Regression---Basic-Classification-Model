# Logistic-Regression---Basic-Classification-Model
Logistic Regression is a popular classification algorithm used for solving binary classification problems (like yes/no, 0/1). This model analyzes input data to predict the probability that the input belongs to a specific class.
This project uses Logistic Regression to predict whether a person has diabetes based on health data. The model is trained on a publicly available diabetes dataset with features like glucose level, BMI, age, and more.

Dataset
The dataset contains health measurements of patients and a target column called Outcome:

0 means no diabetes

1 means diabetes

Steps Performed
Data Loading
Loaded the diabetes dataset CSV using pandas.

Data Exploration
Checked basic statistics, data types, and columns.

Data Preprocessing
Separated features (X) and target (y).
Split the data into training and testing sets.

Feature Scaling
Scaled the feature values for better model performance.

Model Training
Trained a Logistic Regression model on the training data.

Prediction and Evaluation
Predicted on the test set and evaluated using:

Accuracy

Classification report (Precision, Recall, F1-score)

Confusion matrix

ROC curve (optional)
# Sample Output
Accuracy: 0.78
Classification Report:
              precision    recall  f1-score   support

           0       0.80      0.85      0.82       100
           1       0.73      0.65      0.69        54

    accuracy                           0.78       154
   macro avg       0.76      0.75      0.75       154
weighted avg       0.78      0.78      0.78       154

Confusion Matrix:
[[85 15]
 [19 35]]
