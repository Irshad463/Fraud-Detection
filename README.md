# Fraud Detection with Machine Learning

### Overview

This project demonstrates how to detect fraudulent credit card transactions using a Random Forest classifier. The dataset used is the Credit Card Fraud Detection dataset, which contains anonymized credit card transactions labeled as fraudulent or genuine. The project addresses the class imbalance problem using SMOTE (Synthetic Minority Over-sampling Technique) and evaluates the model's performance.

### Key Features

**Data Preprocessing:** Handles imbalanced data using SMOTE to balance the classes.

**Model Training:** Uses Random Forest, a robust algorithm for classification tasks.

**Prediction Interface:** Provides a simple function to predict whether a transaction is fraudulent.

**Model Persistence:** Saves the trained model for future use.

### Results

The Random Forest model achieves the following performance metrics (example values, actual metrics may vary based on the dataset split):

**Precision:** High precision indicates few false positives.

**Recall:** High recall indicates few false negatives.

**F1-Score:** Balanced measure of precision and recall.

### Dependencies

Python 3.10+

**Libraries:**

pandas

scikit-learn

imbalanced-learn

joblib

**Install dependencies using:**

pip install pandas scikit-learn imbalanced-learn joblib

### Usage

**Data Loading:** The dataset is loaded from creditcard.csv.

**Preprocessing:**

Features and target variable are separated.

SMOTE is applied to balance the classes.

**Model Training:**

The dataset is split into training and testing sets.

A Random Forest classifier is trained on the balanced data.

**Prediction:**

Use the predict_fraud function to classify new transactions.

### Future Improvements

**Hyperparameter Tuning:** Optimize the Random Forest parameters using GridSearchCV or RandomizedSearchCV.

**Feature Engineering:** Explore additional features or transformations to improve accuracy.

**Alternative Models:** Experiment with other algorithms like XGBoost or Neural Networks.

**Real-time Deployment:** Create a web API (e.g., Flask) for real-time fraud detection.

### License

This project is open-source under the MIT License.

### Note

The dataset (creditcard.csv) should be placed in the same directory as the notebook or script. Ensure the dataset is properly formatted with the correct feature names and target variable (Class).
