# CodeSoft_task1
# 🚢 Titanic Survival Prediction

This project uses the famous [Titanic dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset) to predict whether a passenger survived or not based on features such as age, gender, ticket class, and more.

---

## 📌 Project Overview

The Titanic dataset is a classic dataset in machine learning, often used for binary classification tasks.  
In this project, we:

- Load and explore the Titanic dataset.
- Preprocess the data (handle missing values, encode categorical variables, etc.).
- Train a machine learning model to predict survival.
- Evaluate the model's accuracy.
- Build a simple **Gradio/Tkinter GUI** to allow users to input passenger details and get survival predictions.

---

## 📂 Dataset Description

The dataset contains the following columns:

| Column        | Description |
|---------------|-------------|
| PassengerId   | Unique ID for each passenger |
| Survived      | Survival (0 = No, 1 = Yes) |
| Pclass        | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name          | Name of passenger |
| Sex           | Gender of passenger |
| Age           | Age in years |
| SibSp         | # of siblings/spouses aboard |
| Parch         | # of parents/children aboard |
| Ticket        | Ticket number |
| Fare          | Passenger fare |
| Cabin         | Cabin number |
| Embarked      | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## ⚙️ Installation & Requirements

Make sure you have Python 3.7+ installed.

Install dependencies:

```bash
pip install pandas numpy scikit-learn gradio
