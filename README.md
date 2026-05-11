# Insurance-Cost-Prediction
Insurance cost prediction  model built using Linear Regression and Python libraries like Pandas and Scikit-learn
# Medical Insurance Cost Prediction using Linear Regression

## 📌 Project Overview

This project aims to predict medical insurance charges using Machine Learning techniques, specifically **Linear Regression**.

The dataset contains demographic, lifestyle, and health-related information such as:

- Age
- Gender
- BMI
- Smoking Status
- Number of Children
- Region
- Hospital Expenditure
- Annual Salary

Insurance companies can use this model to estimate medical costs accurately and design better insurance policies and premium plans.

---

# 🎯 Problem Statement

The objective of this project is to build a predictive model that estimates medical insurance charges based on customer information.

Since insurance costs depend on multiple factors like smoking habits, BMI, and medical expenses, Machine Learning can help identify patterns and predict future insurance charges efficiently.

---

# ⚙️ Solution Approach

The following steps were performed to solve the problem:

## 1. Data Preprocessing

- Handled missing values in numerical and categorical columns
- Filled numerical missing values using mean
- Filled categorical missing values using mode
- Encoded categorical variables into numerical form
- Prepared clean dataset for model training

---

## 2. Exploratory Data Analysis (EDA)

Performed data visualization and analysis using:

- Histograms
- Boxplots
- Correlation analysis

Key observations:

- Smokers tend to have significantly higher insurance charges
- Higher BMI contributes to increased medical costs
- Outliers were present in charges and BMI columns

---

## 3. Feature Scaling

Applied **Standardization** to normalize numerical features and improve model performance.

---

## 4. Model Building

Implemented **Linear Regression** model.

Linear Regression predicts continuous numerical values by finding relationships between independent variables and the target variable.

---

## 5. Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Predicted values were compared with actual insurance charges to measure model accuracy.

---

## 6. Interpretation

Analyzed model coefficients to understand feature importance.

Major factors affecting insurance charges:

- Smoking Status
- BMI
- Hospital Expenditure
- Age

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📂 Project Structure

```bash
├── Mylinearregressionproject.ipynb
├── insurance.csv
├── README.md
