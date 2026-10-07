# Employee Attrition Prediction

A machine learning project that predicts whether an employee is likely to leave an organization based on employee-related factors.

## 📌 Project Overview

Employee attrition is an important problem for organizations because unexpected employee turnover can affect productivity, hiring costs, and workforce planning.

This project uses machine learning to predict employee attrition based on historical employee information such as:

- Age
- Job Role
- Monthly Income
- Job Satisfaction
- Overtime
- Business Travel
- Distance From Home
- Years at Company
- Total Working Years
- Work-Life Balance
- Job Level
- and other employee-related attributes

The project also includes an interactive prediction interface where employee details can be entered and an attrition prediction can be generated.

---

## 🎯 Objective

The main objective of this project is to develop a machine learning system that can predict whether an employee is likely to:

- Stay with the organization
- Leave the organization

The system also provides an estimated probability of attrition.

---

## 📊 Dataset

The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset.

Dataset characteristics:

- **1,470 employee records**
- **35 original columns**
- Employee demographic information
- Job-related information
- Salary information
- Satisfaction-related information
- Work experience information
- Attrition information

### Target Variable

The target variable is `Attrition`.

| Value | Meaning |
|---|---|
| No | Employee stayed |
| Yes | Employee left |

The raw dataset is included in the `data/` directory of this repository.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression
   ↓
Class Balancing
   ↓
Model Evaluation
   ↓
Feature Importance
   ↓
Interactive Prediction GUI
   ↓
Attrition Prediction
