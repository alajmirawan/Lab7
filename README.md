# Advertising Data Analysis & Logistic Regression

## Lab Overview

This lab analyzes an advertising dataset to understand user behavior and predict whether a user will click on an advertisement using **Logistic Regression**.

---

## Dataset

The dataset contains information about users, including:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male
* Clicked on Ad (Target Variable)

---

## Exploratory Data Analysis (EDA)

We explored the data using visualization techniques such as:

* Histogram of Age distribution
* Jointplots to analyze relationships between features
* KDE plots for density estimation
* Pairplot to visualize feature interactions

---

## Data Preprocessing

* Selected only numerical features
* Defined:

  * **X (features)**
  * **y (target: Clicked on Ad)**
* Split the dataset into training and testing sets (70% training, 30% testing)

---

## Model

We used **Logistic Regression** to train a classification model.

---

## Steps Performed

1. Load the dataset
2. Explore and visualize data
3. Select features
4. Split data using `train_test_split`
5. Train Logistic Regression model
6. Make predictions
7. Evaluate the model

---

## Model Evaluation

The model was evaluated using:

* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix

---

## Results

The model successfully predicts whether a user will click on an ad based on input features.

## Notes

* Results may vary depending on train-test split
* Ensure correct column names when running the code
