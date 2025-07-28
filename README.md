# 📘 Student Exam Performance Predictor

This project uses **Linear Regression** to predict student **Exam Scores** based on the number of **Hours Studied**, using a dataset from Kaggle.

---

## 🧠 Objective

To analyze how the number of hours studied by students impacts their performance on exams and build a predictive model that estimates exam scores based on study hours.

---

## 📂 Dataset

**Source**: Kaggle - Student Performance Factors  
(https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)

The dataset contains various features related to students' academic and social environments.  
In this project, we focus on:

- `Hours_Studied` (Input feature)
- `Exam_Score` (Target variable)

---

## 🧹 Data Cleaning

- Checked for missing values.
- Filled numeric columns with **median**.
- Filled categorical columns with **mode**.
- Removed duplicates.

---

## 🔧 Model Workflow

1. **Train-Test Split**: 80% training, 20% testing.
2. **Model**: Linear Regression from scikit-learn.
3. **Evaluation**: Mean Squared Error (MSE), Actual vs Predicted plot.

---

## 📊 Features Used

| Feature        | Description                          |
|----------------|--------------------------------------|
| Hours_Studied  | Number of hours a student studied    |
| Exam_Score     | Exam score achieved by the student   |

---

## 📈 Results

- The Linear Regression model was trained and tested successfully.
- **Mean Squared Error (MSE)** was calculated to evaluate performance.
- Actual vs Predicted results were visualized in a line graph.
