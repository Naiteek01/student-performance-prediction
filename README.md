# Student Performance Prediction

## About the Project

This project is about predicting a student's math score using
different academic and demographic features.

I built this project while learning the basic Machine Learning
workflow, including data analysis, preprocessing, model training
and evaluation.

## Problem Statement

The goal of this project is to predict the mathematics score of
a student based on information such as:

- Gender
- Race/Ethnicity
- Parental level of education
- Lunch
- Test preparation course
- Reading score
- Writing score

## Dataset

I used the Students Performance in Exams dataset from Kaggle.

Dataset:
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

The dataset contains information about students' demographic
details and their performance in different subjects.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Approach

The project follows these steps:

1. Load the dataset
2. Explore and understand the data
3. Perform basic data analysis
4. Separate features and target variable
5. Split the data into training and testing sets
6. Preprocess numerical and categorical features
7. Train Machine Learning models
8. Compare model performance
9. Evaluate the predictions

## Models Used

- Mean Baseline
- Linear Regression
- Random Forest Regression

## Evaluation Metrics

The models are evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

## Project Structure

```text
Student-Performance-Prediction/
│
├── Student_Performance_Prediction.ipynb
├── StudentsPerformance.csv
└── README.md