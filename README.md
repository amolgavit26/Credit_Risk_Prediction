# Credit Risk Prediction 🏦🔍

![Credit Risk](Credit%20Risk.jpg)

A data science project that aims to predict **credit risk** using machine learning models. This notebook walks through data cleaning, exploratory analysis, feature engineering, and model training/tuning to determine the likelihood of loan default.

---

## 📋 Table of Contents

1. [Problem Statement](#problem-statement)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Project Structure](#project-structure)
5. [Approach](#approach)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [License](#license)

---

## 💡 Problem Statement

In the financial world, credit risk refers to the possibility that a borrower may fail to repay a loan, disrupting the lender’s cash flow. This project predicts whether a loan applicant is likely to default using various ML techniques.

---


## 📂 Dataset

The dataset used is assumed to be a structured financial dataset containing:
- Personal information
- Credit history
- Loan details


---

## 🧠 Approach

The notebook follows this step-by-step process:

1. **Data Loading and Cleaning**
   - Removed duplicates
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature relationships
   - Assessed class balance

3. **Feature Engineering**
   - Treated outliers
   - Encoded categorical variables
   - Scaled numerical features

4. **Model Training and Evaluation**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Each with and without hyperparameter tuning

5. **Comparison of Results**
   - Evaluated using accuracy, precision, recall, F1-score

---

## 📊 Results

| Model              | Tuning        | Accuracy |
|-------------------|---------------|----------|
| Logistic Regression | No            | 83.78%   |
| Logistic Regression | Yes           | 74.15%   |
| Decision Tree       | No            | 88.68%   |
| Decision Tree       | Yes           | 92.03%   |
| Random Forest       | No            | 92.31%   |
| Random Forest       | Yes           | 88.28%   |


---

## ✅ Conclusion

- Machine Learning models can effectively predict credit risk when trained on quality data.
- Random Forest with tuning performed best in this case.
- Proper data preprocessing and feature engineering are critical for performance.

---

## 🙌 Acknowledgements

Thanks to all open-source libraries and contributors to the datasets used in this project.
