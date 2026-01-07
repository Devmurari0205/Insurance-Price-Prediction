# 📉 Model Evaluation Report

## 📌 Model Used
- **Algorithm:** Linear Regression
- **Type:** Supervised Machine Learning
- **Target Variable:** Insurance Charges

---

## 🔄 Model Workflow
1. Feature and target variable separation
2. Train-test split
3. Feature scaling
4. Model training using Linear Regression
5. Performance evaluation

---

## 📊 Evaluation Metrics Used

### 1️⃣ Training Score
- Measures how well the model fits the training data

### 2️⃣ Testing Score
- Indicates how well the model generalizes to unseen data

### 3️⃣ Mean Squared Error (MSE)
- Penalizes large prediction errors
- Lower value indicates better performance

### 4️⃣ Mean Absolute Error (MAE)
- Average of absolute differences between actual and predicted values

### 5️⃣ Root Mean Squared Error (RMSE)
- Square root of MSE
- Interpretable in original units (charges)

### 6️⃣ R² Score
- Indicates how much variance in the target variable is explained by the model

---

## 📈 Model Performance Summary
- Training and testing scores are close, indicating **no overfitting**
- Error metrics are within acceptable range
- Model provides stable and interpretable predictions

---

## 🔍 Model Interpretability
- Extracted slope (coefficients) for each feature
- Identified smoking status and BMI as strongest predictors
- Intercept represents base insurance cost

---

## ⚠️ Limitations
- Linear Regression assumes linear relationships
- Sensitive to outliers
- Performance can be improved with advanced models

---

## 🚀 Future Enhancements
- Apply Ridge and Lasso Regression
- Try tree-based models (Random Forest)
- Deploy model using Streamlit or Flask

---

## ✅ Conclusion
The Linear Regression model performs well for predicting insurance charges and serves as a strong baseline model for further improvements.

---
