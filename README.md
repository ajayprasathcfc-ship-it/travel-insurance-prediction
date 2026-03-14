# travel-insurance-prediction
ML model to predict travel insurance purchase using customer demographic and travel data.
# Travel Insurance Purchase Prediction

## Project Overview

This project aims to predict whether a customer will purchase travel insurance using machine learning techniques. By analyzing customer demographic information, travel behavior, and other related factors, the model helps identify potential customers who are more likely to buy travel insurance.

The project applies data preprocessing, exploratory data analysis (EDA), feature selection, and classification algorithms to build an accurate prediction model.

---

## Dataset Description

The dataset contains customer information related to travel insurance purchase decisions. It includes demographic, financial, and travel behavior attributes.

### Features

| Feature             | Description                                        |
| ------------------- | -------------------------------------------------- |
| Age                 | Age of the customer                                |
| Employment Type     | Government or Private sector employee              |
| GraduateOrNot       | Whether the customer is a graduate                 |
| AnnualIncome        | Annual income of the customer                      |
| FamilyMembers       | Number of family members                           |
| ChronicDiseases     | Whether the customer has any chronic disease       |
| FrequentFlyer       | Whether the customer travels frequently            |
| EverTravelledAbroad | Whether the customer has travelled abroad          |
| TravelInsurance     | Target variable (1 = Purchased, 0 = Not Purchased) |

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis

---

## Exploratory Data Analysis

EDA was performed to understand the distribution and relationships between variables.

Key visualizations include:

* Travel insurance purchase distribution
* Age distribution of customers
* Annual income vs insurance purchase
* Frequent flyer vs insurance purchase
* Correlation heatmap

---

## Machine Learning Models Used

The following classification algorithms were applied:

### Logistic Regression

A baseline model used to understand basic classification performance.

### Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

### XGBoost Classifier

An advanced gradient boosting algorithm used to improve predictive performance.

---

## Model Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Final Model Performance

Accuracy: **84%**

Classification Report:

| Class            | Precision | Recall | F1-score |
| ---------------- | --------- | ------ | -------- |
| No Insurance (0) | 0.81      | 0.97   | 0.89     |
| Insurance (1)    | 0.92      | 0.60   | 0.72     |

The model demonstrates strong predictive capability in identifying customers who are unlikely to purchase travel insurance and provides reliable predictions for potential buyers.

---

## Key Insights

The analysis revealed several factors influencing travel insurance purchases:

* Customers with **higher annual income** are more likely to purchase travel insurance.
* **Frequent travelers** are more likely to buy insurance.
* Customers who have **travelled abroad** show a higher probability of purchasing insurance.
* **Age and family size** also influence purchasing behavior.

These insights can help travel companies design better **targeted marketing strategies**.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Project Structure

```
travel-insurance-prediction
│
├── Travel_Insurance_Prediction.ipynb
├── TravelInsurance
```
