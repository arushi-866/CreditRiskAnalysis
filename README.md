# Credit Risk Prediction

This project focuses on predicting credit default risk using various machine learning models, including **Random Forest**, **Support Vector Machine (SVM)**, and **Logistic Regression**. The dataset used contains customer details such as age, income, and debt ratio, which are analyzed and modeled to determine the likelihood of default.

---

## **Project Overview**

Credit risk prediction is crucial for financial institutions to assess the risk of loan defaults. This notebook implements and compares multiple classification algorithms to predict whether a customer is likely to default on their loan.

Key steps performed in this project:
1. Data loading and cleaning (handling missing values).
2. Exploratory Data Analysis (EDA) using Seaborn and Matplotlib.
3. Feature scaling using **StandardScaler**.
4. Splitting data into training and testing sets.
5. Training and evaluating models:
   - **Random Forest Classifier**
   - **Support Vector Machine (SVM)**
   - **Logistic Regression**
6. Model optimization using **GridSearchCV** and **Cross Validation**.
7. Evaluation using **Confusion Matrix**.

---

## **Dataset**
The dataset (`bankloans.csv`) includes the following columns:
- **age**: Customer age.
- **income**: Customer income.
- **debtinc**: Debt-to-income ratio.
- **default**: Target variable (0 = No Default, 1 = Default).

---

## **Technologies & Libraries Used**
- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for ML models, scaling, and evaluation)

---

## **Modeling**
### **Algorithms Implemented**
1. **Random Forest Classifier**
   - Trained with `n_estimators=200`.
   - Cross-validation performed with `cv=10`.

2. **Support Vector Machine (SVM)**
   - Hyperparameter tuning performed using `GridSearchCV`.
   - Parameters tuned: `C`, `gamma`, and `kernel`.

3. **Logistic Regression**
   - Used as a baseline linear classifier.

### **Evaluation Metrics**
- **Accuracy Score**
- **Cross-Validation Score**
- **Confusion Matrix** (visualized as a heatmap).

---

## **Key Results**
- Random Forest and SVM achieved competitive results.
- Logistic Regression provided a simpler yet effective baseline model.
- Hyperparameter tuning improved the performance of the SVM model.

---

## **Visualization**
The notebook includes visualizations for:
- Income vs. Age
- Debt-to-Income Ratio vs. Age
- Confusion Matrix (heatmap)


