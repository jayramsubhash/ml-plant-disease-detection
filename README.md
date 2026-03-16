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

The model needs to predict categories, such as: Healthy leaf , Diseased leaf , Different disease types

Since Linear Regression tries to predict numerical values instead of classes, it does not perform well for this problem. The predictions are continuous numbers and cannot clearly separate disease categories.

Because of this, classification algorithms like: Decision Tree , Random Forest , KNN , SVM , Logistic Regression work better for this project.

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

## Model Accuracy Comparison
Without PCA Algorithm	Accuracy : Decision Tree	20.70%  ,  Logistic Regression	48.18%  ,  KNN (K-Nearest Neighbors)	31.25%  ,  Random Forest	48.83%  ,  SVM (Support Vector Machine)	58.20%
With PCA (Principal Component Analysis) Algorithm	Accuracy : Decision Tree + PCA	45.44%  ,  logistic Regression + PCA	25.39%  ,  KNN + PCA	46.88%  , Random Forest + PCA	57.94%  ,  SVM + PCA	40.23% . 

## Observation
Best model without PCA: SVM (58.20%)
Best model with PCA: Random Forest + PCA (57.94%)
PCA improved performance for Decision Tree and KNN but reduced accuracy for some other models.

## Conclusion
Support Vector Machine achieved the highest accuracy without dimensionality reduction, while Random Forest performed best when PCA was applied.

## How to Run
1. Download the dataset
2. Open `plant_disease_machine.ipynb`
3. Run the notebook cells step by step

