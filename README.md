# unijos-student-performance-prediction
K-Nearest Neighbors (KNN) machine learning project analyzing student performance data associated with the University of Jos.
# UNIJOS Student Performance Analysis Using KNN

## Project Overview

This project applies the K-Nearest Neighbors (KNN) algorithm to a student performance dataset associated with the University of Jos (UNIJOS).

The project explores student data, prepares relevant features, and evaluates a KNN model on the prediction task defined in the notebook.

## Problem Statement

Student performance datasets can reveal patterns in academic outcomes and related factors. Machine learning provides a way to explore whether patterns in existing observations can help predict a defined outcome.

This project demonstrates how KNN can be applied to educational data while highlighting the importance of data preparation and responsible interpretation.

## Objectives

- Explore and understand the student dataset.
- Prepare features for machine learning.
- Implement a KNN model.
- Evaluate model performance.
- Discuss findings and limitations.

## Dataset

**Dataset:** `StudentsPerformance.csv`

The dataset contains student-related information and performance variables. Refer to the notebook for the exact features, target variable, and data source.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Algorithm: K-Nearest Neighbors

KNN is a supervised learning algorithm that predicts an observation's class using the labels of nearby observations in feature space.

Its performance can depend on feature scaling, the choice of K, the distance metric, and the selected features.

## Methodology

1. Load and explore the dataset.
2. Identify the target variable and input features.
3. Prepare the data and encode categorical variables where necessary.
4. Scale features when appropriate.
5. Split the dataset into training and testing sets.
6. Train the KNN classifier.
7. Evaluate predictions on the test set.

## Model Evaluation

| Metric | Result |
|---|---|
| Accuracy | [95] |
| Precision | [1.00] |
| Recall | [0.75] |
| F1-score | [0.86] |
| Selected K | [1]

## How to Run the Project

1. Clone or download this repository.
2. Install the dependencies.
3. Open the Jupyter Notebook.
4. Run the notebook cells in order.

Install the commonly used dependencies with:

`pip install pandas numpy matplotlib seaborn scikit-learn jupyter`

## Limitations

The dataset does not represent any student at UNIJOS. Model performance on the available data does not establish that the same predictions will work for all students or future academic sessions.

Predictions should not be treated as definitive judgments about individual students.

## Conclusion

This project demonstrates a practical application of KNN to student performance data. It strengthens understanding of supervised learning, feature preparation, distance-based classification, and model evaluation.

## Author

Anyagu Chuka

## Project Type

Supervised Machine Learning | Classification (if applicable)
