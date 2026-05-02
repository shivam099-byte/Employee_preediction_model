Employee Salary Prediction using Machine Learning

# Project Overview

This project aims to build a Machine Learning model that predicts an employee’s salary based on their years of experience. The model uses **Simple Linear Regression** to identify the relationship between experience and salary.

---

🎯 Problem Statement

The objective of this project is to predict the salary of an employee using their years of experience.

* **Input Feature:** Years of Experience
* **Target Variable:** Salary

This is a **regression problem** where we estimate continuous numeric values.

---

 📂 Dataset Information

* Dataset Name: Salary Data (Simple Linear Regression)
* Source: Kaggle
* Features:

  * `Years Experience` → Independent Variable
  * `Salary` → Dependent Variable

The dataset is small, clean, and suitable for beginner-level machine learning projects.

---

# Technologies Used

* Python 🐍
* Google Colab
* Libraries:

  * NumPy
  * Pandas
  * Matplotlib
  * Scikit-learn

---

## ⚙️ Project Workflow

# 1️⃣ Data Preprocessing

* Loaded dataset using Pandas
* Checked for missing values
* Selected relevant features
* Split dataset into training and testing sets

---

# 2️⃣ Model Building

* Applied **Linear Regression** model
* Trained the model on training data

---

# 3️⃣ Model Evaluation

* Evaluated model performance using:

  * **R² Score**
  * **Mean Squared Error (MSE)**

---

# 4️⃣ Visualization

* Plotted graph of:

  * Experience vs Salary
  * Regression line

---

## 📊 Results

* The model shows a **strong positive linear relationship** between experience and salary
* Higher experience leads to higher predicted salary
* The model performs well with a high R² score

#Example Prediction

Input:
Years of Experience = 5

Output:
Predicted Salary ≈ (based on trained model)

---

# Future Improvements

* Use larger datasets
* Apply advanced models like:

  * Random Forest
  * Gradient Boosting
* Add multiple features (education, role, location)
* Deploy as a web application

---

 Conclusion

This project demonstrates how Machine Learning can be used to predict employee salaries using a simple regression model. It provides a strong foundation for understanding supervised learning concepts.
