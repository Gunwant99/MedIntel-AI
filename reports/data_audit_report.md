# MedIntel AI - Data Audit Report

Dataset:
Pima Indians Diabetes Dataset

Shape:
768 rows, 9 columns

Features:
Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age

Target:
Outcome

Findings:

- No explicit null values found.
- Hidden missing values represented as 0 detected.

Hidden Missing Values:

Glucose: 5
BloodPressure: 35
SkinThickness: 227
Insulin: 374
BMI: 11

Conclusion:

Data cleaning is required before EDA and model training.