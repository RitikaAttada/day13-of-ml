## 🌟 **Day 13: Mastering Multivariate Linear Regression**

Today, I worked on five structured regression problems involving **multiple input features** that influence a single target value (`Exam_Score`). Each dataset represented different student performance scenarios with the following features:

* `Hours_Studied`
* `Attendance_Rate`
* `Sleep_Hours`
* `Practice_Tests_Taken`
* ➡️ Target: `Exam_Score`

---

## 🧠 **What I Did**

✅ Created 5 multivariate regression datasets with realistic and meaningful features
✅ Trained a Linear Regression model on each dataset
✅ Predicted on sample inputs and compared them to expected `Exam_Score` values
✅ Noticed the model performed well with minor variance due to noise in the data

---

## 🔢 **Sample Inputs**


```python
predict_exam_score(41.40, 3.33, 27.97, 83.11) ➡️ Expected: 208.74
```
```python
predict_exam_score(72.23, 42.42, 40.95, 78.73) ➡️ Expected: 262.27
```
```python
predict_exam_score(14.60, 37.79, 23.77, 42.50) ➡️ Expected: 23.10
```
---

## 🧩 **What I Learned**

* Multivariate regression models are powerful for modeling real-world scenarios.
* Meaningful feature names make datasets easier to understand and debug.
* Evaluating model predictions on sample inputs helps build confidence.
* Small noise in the data reflects realistic uncertainty, making predictions more robust.

---

## 🧭 **Next Steps**

* Try using **R² Score, MAE, and MSE** for model evaluation
* Test **overfitting/underfitting** using larger or smaller datasets
* Introduce **Polynomial Features** for nonlinear effects
* Experiment with **Regularization (Ridge, Lasso)** on these datasets

---

