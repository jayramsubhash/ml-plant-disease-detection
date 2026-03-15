# ML Plant Disease Detection

This project detects plant diseases using Machine Learning algorithms.

## Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest
- SVM
- KNN

## Why Linear Regression and Multiple Linear Regression did not work

Linear Regression and Multiple Linear Regression are mainly used for predicting continuous values.
For example:

predicting house price

predicting temperature

predicting sales amount

But in this project, the task is classification, not prediction of numbers.

The model needs to predict categories, such as:

Healthy leaf

Diseased leaf

Different disease types

Since Linear Regression tries to predict numerical values instead of classes, it does not perform well for this problem. The predictions are continuous numbers and cannot clearly separate disease categories.

Because of this, classification algorithms like:

Decision Tree

Random Forest

KNN

SVM

Logistic Regression

work better for this project.

## Dataset
Plant leaf disease dataset containing healthy and diseased leaves.

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Workflow
1. Load dataset
2. Data preprocessing
3. Feature extraction
4. Train multiple ML models
5. Compare accuracy
6. Predict plant disease

## Results
Random Forest achieved the highest accuracy.

## How to Run
1. Download the dataset
2. Open `plant_disease_machine.ipynb`
3. Run the notebook cells step by step

