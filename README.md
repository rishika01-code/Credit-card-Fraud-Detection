# Credit-card-Fraud-Detection using Machine Learning
ML-based credit card fraud detection system with imbalanced dataset handling and model performance comparison

## 📌 Project Overview

Credit card fraud has become one of the biggest challenges in digital banking and online transactions. This project uses Machine Learning techniques to classify credit card transactions as *Fraudulent* or *Legitimate* based on historical transaction data.

The project compares multiple machine learning algorithms and evaluates their performance using standard classification metrics.

---
## 🎯 Objective

The primary objective of this project is to build an accurate machine learning model capable of detecting fraudulent credit card transactions while minimizing incorrect predictions.

## 📂 Dataset

- *Dataset:* Credit Card Fraud Detection Dataset
- *Total Transactions:* 284,807
- *Legitimate Transactions:* 284,315
- *Fraudulent Transactions:* 492

The original dataset is highly imbalanced. To reduce model bias during training, a balanced dataset was created by randomly selecting *492 legitimate transactions* and combining them with *492 fraudulent transactions*.
---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git & GitHub

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---
## ⚙️ Project Workflow

1. Import required libraries
2. Load the dataset
3. Data preprocessing
   - Remove unnecessary Time column
4. Analyze class imbalance
5. Balance the dataset using random undersampling
6. Split data into training and testing sets
7. Train multiple machine learning models
8. Evaluate model performance
9. Compare model accuracies
10. Visualize results using confusion matrix and bar chart

---

## 📊 Model Performance

| Model | Test Accuracy |
|--------|--------------|
| Logistic Regression | *93.40%* |
| Random Forest | *91.88%* |
| Gradient Boosting | *91.37%* |

*Best Performing Model:* Logistic Regression

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📷 Results

### Accuracy Comparison
![image alt](https://github.com/rishika01-code/Credit-card-Fraud-Detection/blob/b15c4de2020ad1d5cb279604f8dfe0693dcb6b90/Screenshot%202026-07-14%20100522.png)
### Confusion Matrix



---





