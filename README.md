# Student Performance Analysis and Prediction

## Project Overview
This project focuses on analyzing the factors that affect student performance and building machine learning models to **predict exam scores**.  
It includes data preprocessing, exploratory data analysis (EDA), feature selection, and the training and evaluation of multiple regression models.

The models used include:
- **Linear Regression**
- **Lasso Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**


## Objectives
- Identify key factors influencing student performance.  
- Build and compare multiple regression models.  
- Evaluate models using performance metrics like **R²**, **MAE**, and **RMSE**.  


## Dataset
**File:** `StudentPerformanceFactors.csv`

### 🔑 Key Features

| Feature | Description | Type |
|----------|--------------|------|
| `Hours_Studied` | Number of hours a student studies | Integer |
| `Attendance` | Attendance percentage | Integer |
| `Parental_Involvement` | Level of parental involvement | Categorical |
| `Access_to_Resources` | Availability of study materials/resources | Categorical |
| `Extracurricular_Activities` | Participation in extracurricular activities | Categorical |
| `Sleep_Hours` | Average sleep hours per day | Integer |
| `Previous_Scores` | Previous academic performance | Integer |
| `Motivation_Level` | Level of student motivation | Categorical |
| `Family_Income` | Family income level | Categorical |
| `Teacher_Quality` | Quality of teaching received | Categorical |
| `School_Type` | Type of school attended | Categorical |
| `Peer_Influence` | Influence of peers on study habits | Categorical |
| `Physical_Activity` | Level of physical activity per week | Integer |
| `Learning_Disabilities` | Whether the student has learning disabilities | Categorical |
| `Parental_Education_Level` | Highest education level of parents | Categorical |
| `Distance_from_Home` | Distance between home and school | Categorical |
| `Gender` | Student’s gender | Categorical |
| `Exam_Score` | Final exam score (Target Variable) | Integer |
