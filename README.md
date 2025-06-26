# 🎓 Student Performance Predictive Analytics

This project analyzes and predicts student performance using the **StudentsPerformance.csv** dataset. It includes:

- Data cleaning and encoding
- Exploratory Data Analysis (EDA)
- A regression model to predict math scores
- A classification model to predict high-performing students (math score > 70)

---

## 📂 Dataset Overview

The dataset contains student attributes like:
- Gender
- Race/Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Math, Reading, and Writing scores

---

## 📊 Exploratory Data Analysis (EDA)

- Visualized the distribution of test scores
- Analyzed the correlation between all numeric features
- Observed how test preparation and parental education relate to scores

---

## 🔁 Data Cleaning & Feature Engineering

- Converted categorical variables to numerical format using label encoding
- Created a binary target variable for classification (`math_score_high` = 1 if score > 70)

---

## 📈 Regression Model – Predict Math Score

**Model**: Linear Regression  
**Evaluation**:
- Mean Absolute Error (MAE): ~4.13
- Root Mean Squared Error (RMSE): ~5.28
- R² Score: 0.885 ✅

👉 This means the model explains ~88.5% of the variation in math scores.

---

## 🔍 Classification Model – Predict High Score (Math > 70)

**Model**: Decision Tree Classifier  
**Evaluation**:
- Accuracy: 81.5%
- Precision, Recall, F1-score evaluated on both classes (≤70 and >70)
- Confusion Matrix analyzed

---

## 📁 Files Included

- `StudentsPerformance.csv`: Raw dataset
- `student_performance_analysis.ipynb`: Jupyter Notebook with full workflow
- `README.md`: Project documentation

---

## 💡 Future Improvements

- Hyperparameter tuning for better model performance
- Include feature selection and scaling
- Try alternative models like Random Forest, Logistic Regression, etc.

---

## 🙋‍♀️ About Me

Hi, I’m **Nidhi Kapadia**, a Predictive Analytics student at Conestoga College with a deep love for math, statistics, and real-world problem solving through data.

📬 Connect with me: [LinkedIn](https://www.linkedin.com/in/nidhi-kapadia-144122365/)  
🌐 Portfolio coming soon...

---
