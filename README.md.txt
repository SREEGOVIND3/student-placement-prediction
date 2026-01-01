# Student Placement Prediction using Machine Learning

## Overview
This project aims to predict whether a student will be placed or not based on academic performance, skills, and training-related attributes. The project applies data analysis and machine learning techniques to uncover key factors influencing placement outcomes.

## Problem Statement
Educational institutions and students often seek to understand which factors most significantly impact placement success. Using historical placement data, this project builds a classification model to predict placement status.

## Objectives
- Perform Exploratory Data Analysis (EDA) to identify trends and patterns in student placement data.
- Understand the relationship between academic performance, skills, and placement outcomes.
- Build a machine learning classification model to predict placement status.
- Evaluate model performance using standard metrics.
- Achieve a minimum prediction accuracy of 60%.

## Dataset
The dataset contains student-level information including:
- Academic scores (SSC, HSC, CGPA)
- Internships and project experience
- Certifications and workshops
- Aptitude test scores
- Soft skill ratings
- Placement training details

**Target Variable:**  
- `PlacementStatus` (Placed / Not Placed)

## Machine Learning Task
- **Type:** Binary Classification
- **Algorithms Used:** Logistic Regression (baseline model)

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure
student-placement-prediction/
│
├── data/
│   └── placement.csv
│
├── notebooks/
│   └── student_placement_analysis.ipynb
│
├── images/
│   └── eda_visualizations.png
│
└── README.md

## Expected Outcomes
- Visual insights highlighting factors influencing placement.
- A trained machine learning model for placement prediction.
- Performance metrics including accuracy and confusion matrix.
  
## Results
A Logistic Regression model was trained on the processed dataset and achieved an accuracy of approximately **79.45%** on the test data, demonstrating effective prediction of student placement outcomes.

## Conclusion
This project demonstrates a practical application of machine learning in the education domain and highlights how data-driven approaches can support career outcome predictions.



