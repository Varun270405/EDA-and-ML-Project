# 📚 Student Habits and Academic Performance Prediction using Machine Learning

## 📌 Project Overview

This project analyzes the relationship between students' daily habits and their academic performance using **Exploratory Data Analysis (EDA)** and **Machine Learning Regression** techniques. The objective is to identify the factors that significantly influence exam scores and build predictive models to estimate student performance.

---

## 🎯 Problem Statement

To analyze students' lifestyle and study habits, identify the key factors affecting academic performance, and develop an accurate regression model to predict students' exam scores.

---

## 📂 Dataset

The dataset contains information related to students' academic and lifestyle habits, including:

* Study Hours
* Attendance Percentage
* Sleep Hours
* Diet Quality
* Internet Quality
* Social Media Usage
* Netflix Hours
* Exercise Frequency
* Mental Health Rating
* Exam Score (Target Variable)

---

## 🛠 Data Preprocessing

* Removed unnecessary columns (`student_id`)
* Handled missing values
* Checked and removed duplicate records
* Categorical Encoding using:

  * Mapping (Ordinal/Binary Encoding)
  * One-Hot Encoding (`get_dummies`)
* Data Cleaning and Feature Engineering

---

## 📊 Exploratory Data Analysis (EDA)

Performed **15 meaningful visualizations** following the **UBM Rule**:

* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis

Key visualizations include:

* Histograms
* Bar Charts
* Box Plots
* Scatter Plots
* Correlation Heatmap
* Pair Plot

---

## 🤖 Machine Learning Models

The following regression models were implemented:

* Linear Regression
* Lasso Regression
* Ridge Regression

Hyperparameter tuning was performed using **GridSearchCV**.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)
* R² Score

---

## 🔍 Model Explainability

Feature importance was analyzed using model coefficients and explainability techniques to identify the variables that most influence students' exam scores.

---

## 📌 Key Insights

* Higher study hours and attendance positively influence exam scores.
* Healthy lifestyle habits contribute to better academic performance.
* Excessive social media and entertainment usage negatively impact exam scores.
* Ridge Regression provided a robust and reliable predictive model after hyperparameter tuning.

---

## 💻 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Future Improvements

* Implement advanced ensemble models such as Random Forest and XGBoost.
* Deploy the final model using Flask or Streamlit.
* Develop an interactive dashboard for performance prediction.

---

## 📜 Conclusion

This project demonstrates how EDA and Machine Learning can be used to analyze student behavior and accurately predict academic performance. The insights can help educational institutions make data-driven decisions to improve student outcomes.
