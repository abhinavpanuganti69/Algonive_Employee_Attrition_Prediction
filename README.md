# Algonive_Employee_Attrition_Prediction


# Employee Attrition Prediction

## Project Overview

This project aims to predict employee attrition using machine learning models.
The objective is to identify employees at risk of leaving and analyze the key factors influencing attrition.

Dataset used: **IBM HR Analytics Employee Attrition Dataset**

---

## Problem Statement

Employee attrition is a major concern for organizations.
The goal of this project is to:

* Predict whether an employee is likely to leave.
* Handle class imbalance effectively.
* Extract business insights to support HR decision-making.

---

## Dataset Information

* Total Records: 1470 employees
* Features after preprocessing: 44
* Attrition Rate: ~16% (imbalanced dataset)

---

## Data Preprocessing

* Removed non-informative columns (EmployeeNumber, StandardHours, etc.)
* Converted target variable to binary format
* Applied binary encoding and one-hot encoding
* Used stratified train-test split (80-20)

---

## Models Implemented

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Balanced Logistic Regression
5. Balanced Decision Tree
6. Tuned Random Forest

---

## Model Performance Summary

| Model                        | Accuracy | Recall (Attrition) |
| ---------------------------- | -------- | ------------------ |
| Logistic Regression          | 86%      | 34%                |
| Decision Tree                | 76%      | 36%                |
| Random Forest                | 83%      | 6%                 |
| Balanced Logistic Regression | **75%**  | **62%**            |
| Balanced Decision Tree       | 77%      | 53%                |
| Balanced Random Forest       | 82%      | 13%                |

Final Model Selected: **Balanced Logistic Regression**

* Recall (Attrition): 62%
* AUC Score: 0.79

---

## Key Business Insights

* Overtime significantly increases attrition risk.
* Employees with frequent business travel show higher attrition.
* Sales and Laboratory roles have higher turnover.
* Lack of promotion increases probability of leaving.
* Higher job satisfaction and strong manager relationships reduce attrition.

---

## Business Recommendations

* Reduce excessive overtime workload.
* Monitor employees with frequent travel schedules.
* Improve promotion cycles.
* Strengthen manager-employee engagement.
* Implement retention strategies for high-risk roles.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

---

## Conclusion

Balanced Logistic Regression performed best in identifying employees likely to leave while maintaining strong overall performance.

The model and insights can help organizations proactively reduce employee attrition and improve retention strategies.

---

Do you want me to:

* Draft your LinkedIn post?
* Or help you script your demo video?

Let’s finish this like pros 😌🔥
