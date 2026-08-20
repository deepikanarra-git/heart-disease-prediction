# Heart Disease Prediction Using Machine Learning

## Project Overview

This project uses machine learning to predict the presence of heart disease from clinical patient data.

The project is implemented in Python using the UCI Heart Disease dataset. It is a binary classification problem where the target indicates whether heart disease is present or absent.

## Objective

The main objective is to build and compare machine learning classification models and identify the model that performs best on the given dataset.

## Dataset

The dataset contains clinical information about 303 patients and 14 variables.

### Features

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- ST depression (oldpeak)
- Slope of the ST segment (slope)
- Number of major vessels (ca)
- Thalassemia (thal)

### Target

The original `num` variable was converted into a binary target:

- `0` → No heart disease
- `1` → Heart disease present

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Load the dataset
2. Inspect the dataset structure
3. Assign meaningful column names
4. Check data types
5. Identify missing values
6. Clean the dataset
7. Create the binary target variable
8. Perform exploratory data analysis
9. Separate features and target
10. Split data into training and testing sets
11. Scale features for Logistic Regression
12. Train Logistic Regression
13. Train Decision Tree
14. Train Random Forest
15. Compare model performance
16. Evaluate the best-performing model

## Models Used

### Logistic Regression

Used as a baseline classification model.

### Decision Tree

Used to model decision rules based on the clinical features.

### Random Forest

An ensemble of decision trees used to improve predictive performance.

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 83.33% |
| Decision Tree | 75.00% |
| Random Forest | 86.67% |

Random Forest achieved the highest accuracy among the models tested.

### Best Model: Random Forest

The Random Forest model achieved the best performance among the models tested.

- Accuracy: 86.67%
- Precision: 88.46%
- Recall: 82.14%
- F1-score: 85.19%

The model was evaluated on a separate test set containing 60 patient records.
### Random Forest Performance

- Accuracy: 86.67%
- Precision: 88.46%
- Recall: 82.14%
- F1-score: 85.19%

## Important Note

This project is intended for educational and machine learning portfolio purposes. It is not a medical diagnostic system and should not be used to make clinical decisions.

## Future Improvements

- Perform cross-validation
- Tune model hyperparameters
- Compare additional classification algorithms
- Perform deeper feature analysis
- Improve model interpretability
- Develop a simple prediction interface

## Author

Deepika Narra

B.Tech Biotechnology | Aspiring Data Analyst / Data Scientist
