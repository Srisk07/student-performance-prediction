# Student Score Prediction using Linear Regression

This project builds a **Linear Regression model** to predict a student's **Math Score** using their **Reading Score** and **Writing Score**.  
The dataset contains exam scores and is used to perform **exploratory data analysis**, **model training**, **evaluation**, and **prediction** for new students.

---

## 📌 Project Overview

This project includes:

- Loading and exploring the dataset (`exams.csv`)
- Data visualization (Reading vs Math)
- Feature scaling using **StandardScaler**
- Splitting data into train/test sets
- Training a **Linear Regression** model
- Evaluating the model using:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² Score
- Making predictions for new students
- Saving trained model & scaler using `joblib`

---

## 📁 Files in This Project

| File Name | Description |
|----------|-------------|
| `student_.py` | Main script with full model pipeline |
| `exams.csv` | Input dataset (scores of students) |
| `student_linear_model.joblib` | Saved trained ML model |
| `student_scaler.joblib` | Saved StandardScaler |

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/student-score-prediction.git
cd student-score-prediction
