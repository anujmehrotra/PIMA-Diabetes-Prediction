# PIMA Diabetes Prediction using Artificial Neural Network (PyTorch)

This project implements a deep learning approach to predict the likelihood of diabetes using the **PIMA Indians Diabetes Dataset**. The dataset contains diagnostic measurements for female patients of Pima Indian heritage, including features such as glucose levels, BMI, insulin, age, and more. The goal is to classify whether a patient is likely to develop diabetes based on these medical attributes.

## 🔍 Project Overview

* **Framework:** PyTorch
* **Model:** Artificial Neural Network (ANN)
* **Dataset:** PIMA Indians Diabetes Dataset (from UCI Repository / Kaggle)
* **Task:** Binary Classification – Predict whether a patient has diabetes (`1`) or not (`0`).

## 🛠️ Implementation Details

* Data preprocessing: handling missing values, normalization, and train-test split.
* Built a fully connected ANN with hidden layers, ReLU activation, and dropout (if used).
* Loss Function: Binary Cross-Entropy Loss
* Optimizer: Adam
* Performance evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

## 📊 Results

* The ANN successfully learns patterns from the dataset and achieves promising accuracy on the test set.
* Model performance is compared against baseline methods (if implemented).

## 🚀 Future Improvements

* Hyperparameter tuning for better performance.
* Experimenting with deeper architectures and regularization techniques.
* Comparing ANN performance with other ML algorithms like Logistic Regression, Random Forest, or SVM.

## 📂 Repository Contents

* `pima_diabetes_ann.ipynb` – Jupyter Notebook with full implementation
* `README.md` – Project documentation

---

✨ This project demonstrates how deep learning techniques can be applied to healthcare data for early disease prediction.
