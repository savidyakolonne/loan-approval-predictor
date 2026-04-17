# Loan Prediction ML Project

This repository contains a machine learning project developed as part of a university assessment for **Machine Learning & Data Mining**.

The project focuses on building predictive models for:

* Loan Approval Classification
* Maximum Loan Amount Regression

The work follows a structured approach inspired by CRISP-DM, covering data understanding, preprocessing, modelling, evaluation, and optimisation.

---

## 🎯 Objectives

* Predict whether a client’s loan application will be approved or rejected
* Estimate the maximum loan amount for approved clients
* Compare performance of multiple machine learning algorithms
* Apply hyperparameter tuning and ensemble learning
* Critically evaluate model performance and limitations

---

## 📊 Dataset

The dataset contains anonymised financial and demographic information such as:

* Age, Income, Employment Length
* Credit History, Loan Amount, Interest Rate
* Loan-to-Income Ratio (LTI)
* Loan Approval Status (target for classification)
* Maximum Loan Amount (target for regression)

---

## 📁 Project Structure

```
├── notebook1_data_preprocessing.ipynb
├── notebook2_classification.ipynb
├── notebook3_regression_ensemble.ipynb
├── data/
├── README.md
```

---

## 📘 Notebooks Overview

### 1️⃣ Data Understanding & Preprocessing

* Data exploration and descriptive statistics
* Handling missing values and inconsistencies
* Feature selection and transformation
* Dataset preparation for:

  * Classification
  * Regression

---

### 2️⃣ Classification Modelling & Tuning

**Models implemented:**

* Naïve Bayes (NB)
* K-Nearest Neighbours (KNN)
* Logistic Regression (LR)

**Key tasks:**

* Train-test split with stratification
* Model evaluation using:

  * Confusion Matrix
  * Precision, Recall, F1-score
  * AUC-ROC
* Hyperparameter tuning using GridSearchCV
* Selection of best-performing model

---

### 3️⃣ Regression & Ensemble Learning

* Decision Tree Regression:

  * Fully grown tree
  * Pruned tree (depth-limited)

* Evaluation using:

  * MAE
  * MSE
  * R²

* Ensemble Learning:

  * Voting Classifier combining two base models

* Performance comparison between:

  * Individual models
  * Ensemble model

---

## ⚙️ Technologies Used

* Python
* NumPy, Pandas
* Scikit-learn
* Matplotlib

---

## 📈 Key Learning Outcomes

* Data preprocessing and feature engineering
* Model training, validation, and optimisation
* Understanding trade-offs between different algorithms
* Applying evaluation metrics based on business goals
* Interpreting results for real-world financial decisions

---

## ⚠️ Notes

* This project is part of an academic assessment
* Results and interpretations are aligned with coursework requirements
* Dataset is anonymised and used for educational purposes only

---

## 🚀 How to Run

1. Clone the repository

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Open notebooks:

```
jupyter notebook
```

---

## 👨‍💻 Author

**Savidya Kolonne**
