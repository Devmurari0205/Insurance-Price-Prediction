# 🏥 Insurance Price Prediction using Python (Linear Regression)

## 📌 Project Overview
This project focuses on predicting **medical insurance charges** based on customer demographic and health-related attributes using **Linear Regression**.  
The goal is to help insurance companies estimate policy pricing more accurately by analyzing historical data.

---

## 🎯 Business Problem
Insurance companies need a reliable way to estimate insurance charges for customers based on factors like:
- Age
- BMI
- Smoking habits
- Region
- Number of children

Accurate prediction helps in:
- Risk assessment
- Fair pricing
- Better customer segmentation

---

## 📂 Dataset Information
The dataset contains the following columns:

| Column Name | Description |
|------------|------------|
| age | Age of the insured person |
| sex | Gender (male/female) |
| bmi | Body Mass Index |
| children | Number of children |
| smoker | Smoking status (yes/no) |
| region | Residential region |
| charges | Medical insurance cost (Target Variable) |

---

## 🛠️ Tools & Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1️⃣ Data Exploration & Preprocessing
- Loaded dataset using Pandas
- Handled missing values:
  - Filled `children` null values with 0
  - Replaced `BMI` null values with mean
- Performed:
  - Scatter plot (Age vs Children)
  - Bar plot (BMI vs Children)
- Applied:
  - Label Encoding for categorical variables
  - Feature Scaling

---

### 2️⃣ Model Building
- Separated features and target variable
- Implemented **Linear Regression**
- Split data into training and testing sets

---

### 3️⃣ Model Evaluation
Evaluated the model using:
- Training Score
- Testing Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Extracted slope (coefficients) and intercept

---

## 📊 Key Results
- Linear Regression successfully modeled insurance charges
- Smoking status and BMI showed strong influence on charges
- Model achieved good generalization with minimal overfitting

---

## 📁 Project Structure
Insurance-Price-Prediction/
 ├── data/
 ├── notebooks/
 ├── business_requirements/
 ├── reports/
 ├── visuals/
 ├── requirements.txt
  README.md

👤 Author
- Harsh Devmurari
- Aspiring Data Analyst | Python | SQL | Machine Learning
