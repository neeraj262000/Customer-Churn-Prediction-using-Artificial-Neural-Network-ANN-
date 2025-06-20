# 🔁 Customer Churn Prediction using Artificial Neural Network (ANN)

This project demonstrates how to use an Artificial Neural Network to predict customer churn — whether a customer is likely to stop using a service — based on a set of customer-related features.

## 📘 Project Summary

Customer churn is a critical metric in subscription-based businesses. Accurately predicting churn allows businesses to proactively take action and retain valuable customers. This project builds a deep learning model using Keras to classify customers as churned or retained.

## 📁 Included File

- `ANN - Customer Churn Prediction_3.0.ipynb`: The full Jupyter Notebook containing data preprocessing, model training, evaluation, and predictions.

## 📊 Dataset Overview

The dataset includes various customer-related attributes, typically:
- **Credit Score**
- **Geography**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited** (Target Variable - 1: Churned, 0: Retained)

> The actual dataset should be loaded or referenced in the notebook.

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib & Seaborn

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Encoding categorical features
   - Feature scaling
   - Splitting into train/test sets

2. **Model Construction**
   - Build a Sequential ANN model using Keras
   - Hidden layers with ReLU activation
   - Output layer with Sigmoid for binary classification

3. **Training & Evaluation**
   - Fit model on training data
   - Evaluate with accuracy, confusion matrix, and classification report

4. **Predictions**
   - Predict individual customer churn probability
   - Interpret results for business insights

## 📈 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score

## ▶️ How to Run

1. Clone this repository.
2. Install the required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
