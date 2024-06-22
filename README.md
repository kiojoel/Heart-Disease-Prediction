# Heart Disease Prediction

## Introduction

Heart disease is a major health issue globally, responsible for numerous deaths each year. Early detection and treatment can significantly improve patient outcomes.
This project aims to develop a predictive model for heart disease using patient health metrics, aiding in the timely diagnosis and treatment of this condition.

## Dataset

The dataset used for this project contains the following features:
- **age**: Age of the patient
- **sex**: Sex of the patient (1 = male; 0 = female)
- **cp**: Chest pain type (0, 1, 2, 3)
- **trestbps**: Resting blood pressure (in mm Hg on admission to the hospital)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results (0, 1, 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: The slope of the peak exercise ST segment (0, 1, 2)
- **ca**: Number of major vessels (0-4) colored by fluoroscopy
- **thal**: Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect)
- **target**: Presence of heart disease (1 = yes; 0 = no)

## Project Workflow

1. **Data Collection and Processing**:
2. **Exploratory Data Analysis (EDA)**:
    - Summary statistics of the dataset.
    - Distribution plots for each feature, comparing patients with and without heart disease.
    - Correlation matrix to understand relationships between features.

3. **Modeling**:
    - Splitting the data into training and testing sets.
    - Training machine learning model (logistic regression).
    - Evaluating model performance using appropriate metrics (accuracy).

4. **Conclusion**:
    - Make Predictions.
    - Summarizing findings.
