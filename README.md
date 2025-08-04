# 📘 Predict Student Scores from Study Hours

## 📌 Description

This beginner-friendly project demonstrates how to use **Linear Regression** to predict student scores based on the number of hours they study. The goal is to build an end-to-end regression pipeline — from data loading to model evaluation and prediction — using Python and scikit-learn.

---

## 🔗 Dataset

The dataset used is the classic [Student Scores Dataset](https://raw.githubusercontent.com/AdiPersonalWorks/Random/master/student_scores%20-%20student_scores.csv) from GitHub.  
It includes the following columns:

- `Hours`: Number of hours a student studies
- `Scores`: Corresponding score in the test

---

## 🧠 Objective

- Build a linear regression model to predict student scores.
- Evaluate the model using **Mean Squared Error (MSE)** and **R² Score**.
- Visualize data trends and model predictions.
- Predict test score for a new student who studies 9.25 hours.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## 🧪 Model Evaluation

- **Mean Squared Error (MSE):** 18.94
- **R² Score:** 0.968

### 📈 Interpretation:

- ✅ **R² ≈ 0.968**: Your model explains approximately **96.8%** of the variance in student scores.  
- ✅ **RMSE ≈ 4.35**: The typical prediction error is about 4.35 score points — a small error range considering test scores.

| R² Value Range | Interpretation    |
|----------------|-------------------|
| 0.0 – 0.3      | Weak fit          |
| 0.3 – 0.6      | Moderate fit      |
| 0.6 – 0.8      | Good fit          |
| 0.8 – 1.0      | Very strong fit ✅ |

---

## 📊 Visualizations

- 📌 Scatter plot of Hours vs Scores
- 📌 Regression line (Actual vs Predicted)
- 📌 Prediction for new value (9.25 hours)

---

## 📂 Folder Structure

