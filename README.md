# Logistic-Regression-Project
Objective of this project is to predict the need for hospitalization among COVID-affected patients using a logistic regression model. By analyzing certain patient attributes, the model aims to classify each patient into one of two categories: "Needs Hospitalization" or "Does Not Need Hospitalization".

# Features Used
1. Age: Patient’s age
2. Body Temperature: The severity of temperature abnormalities (e.g., Normal, Moderate, High)
3. Chronic Disease: Indicates if the patient has underlying chronic conditions (yes/no)
4. Breathing Issue: Indicates if the patient has reported breathing difficulties (yes/no)
5. Blood Oxygen Level: Percentage of blood oxygen level
6. The target variable is Hospitalization Requirement, which indicates if a patient needs to be hospitalized (yes/no).

# Project Workflow

## Data Preprocessing:
Handling missing values in numerical features (e.g., Age, Blood Oxygen Level).
Encoding categorical features (e.g., Body Temperature, Chronic Disease).
Standardizing numerical values for consistent scaling.

## Model Training:
Implementing logistic regression to train the model.
Splitting the data into training and testing sets for model evaluation.

## Evaluation:
Using accuracy scores and a confusion matrix to evaluate the model's performance on predicting hospitalization needs.
Visualizing results using a confusion matrix heatmap for clarity.

## Results
The model provides a predictive probability that indicates the likelihood of hospitalization for each patient. This can aid healthcare providers in making timely and data-informed decisions for COVID-affected patients, helping allocate resources efficiently.

## Usage
To run the model:

Ensure all dependencies are installed (e.g., scikit-learn, pandas, numpy, matplotlib, seaborn).
Load the dataset and preprocess it as described.
Train the logistic regression model and evaluate its performance on the test set.


This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
