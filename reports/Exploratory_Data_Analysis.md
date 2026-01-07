# 📊 Exploratory Data Analysis (EDA)

## 📌 Objective
The purpose of Exploratory Data Analysis (EDA) is to understand the structure, patterns, and relationships within the insurance dataset before building a machine learning model.

---

## 📂 Dataset Overview
- Rows: 1300+ insurance records
- Columns: 7 features
- Target Variable: `charges`

### Features:
- `age` – Age of the insured person
- `sex` – Gender (male/female)
- `bmi` – Body Mass Index
- `children` – Number of children
- `smoker` – Smoking status (yes/no)
- `region` – Residential region
- `charges` – Medical insurance cost

---

## 🧹 Data Cleaning
- Filled missing values in `children` column with **0**
- Replaced missing values in `bmi` column using **mean value**
- Verified no duplicate records
- Ensured correct data types

---

## 📈 Data Visualization & Insights

### 1️⃣ Age vs Children (Scatter Plot)
- Most policyholders have 0–2 children
- No strong correlation between age and number of children

### 2️⃣ BMI vs Children (Bar Plot)
- BMI values are distributed across all child categories
- Higher BMI does not strongly depend on number of children

---

## 🔍 Key Observations
- Smoking status has a strong impact on insurance charges
- Higher BMI often leads to higher medical costs
- Age shows a positive relationship with insurance charges
- Region has minimal impact compared to health-related factors

---

## 📌 Conclusion
EDA revealed that **age, BMI, and smoking status** are the most influential features.  
The dataset is suitable for regression modeling after encoding and scaling.

---
