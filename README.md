# Heart Disease Prediction using Machine Learning

A beginner-level machine learning classification project that predicts the presence or absence of heart disease using clinical patient data.

## Project Overview

The objective of this project is to build a machine learning classification model that predicts whether a patient is likely to have heart disease based on clinical features.

The project follows a complete basic machine learning workflow:

1. Load the dataset
2. Understand the dataset structure
3. Clean the data
4. Handle missing values
5. Prepare the target variable
6. Separate features and target
7. Split the data into training and testing sets
8. Train machine learning models
9. Evaluate model performance
10. Compare the models
11. Select the best-performing model

## Dataset

The project uses the Cleveland heart disease dataset.

- **Total records:** 303
- **Total columns:** 14
- **Target variable:** `num`
- **Classification type:** Binary classification

The original `num` variable contains multiple disease levels. For this project, it was converted into a binary target:

- `0` → No heart disease
- `1` → Presence of heart disease

The binary target was created using:

```python
df_clean["target"] = (df_clean["num"] > 0).astype(int)
