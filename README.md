# 🛳 Titanic Survival Prediction - Machine Learning Project

## Project Overview

This project uses the [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) to predict which passengers were likely to survive the disaster. It walks through the complete machine learning pipeline — from data cleaning and exploration to model training, evaluation, and prediction.

Two models were trained and compared:
- **Logistic Regression** (baseline model)
- **Random Forest Classifier** (advanced model)

I also compared model performance against a rule-based prediction (gender-based baseline) to demonstrate the advantage of learning from multiple features.

---

## Setup Instructions

This project is designed to be run in **Google Colab**, but it will also work in any environment with Python 3 and the required libraries.

---

##  How to Run the Code

1. **Open the Notebook**: Upload or open the `.ipynb` notebook file in [Google Colab](https://colab.research.google.com/).

2. **Upload the Required Files**:
   - first create folder titled `titanic` and place all files below in it
   - `train.csv`
   - `test.csv`
   - *(Optional)* `gender_submission.csv` for baseline comparison

4. **Run All Cells in Order**:
   - Step 1: Load data  
   - Step 2: Explore and understand data  
   - Step 3–4: Clean and preprocess data  
   - Step 5–7: Train Logistic Regression and Random Forest  
   - Step 8: Evaluate models  
   - Step 9: Make predictions on test set  
   - Bonus Steps: Compare to gender-based baseline & More Visualization (ROC Curve, Feature Importance, Confusion Matrix)

---

## 📈 Key Results

- **Random Forest Model** achieved the best accuracy (~84%) and outperformed the simple gender-based rule.
- **Important features**: Sex, Passenger Class, Fare, and Age
- **Feature importance** and **confusion matrices** are visualized to support model interpretation.

---

## 📎 Files Included

| File                    | Description                                           |
|-------------------------|-------------------------------------------------------|
| `train.csv`             | Training data with features and survival labels       |
| `test.csv`              | Test data without labels (for prediction)             |
| `gender_submission.csv` | Optional baseline prediction file                     |
| `titanic_predictions.csv` | Your model's predictions (output)                 |
| `titanic_notebook.ipynb` | Complete notebook with code, visuals, and analysis |
| `README.md`             | Project overview and instructions                     |

---

