# Data Folder

## Overview
The **Data** folder contains several important datasets and documentation files used for the **Diabetes Readmission Prediction** project. These files are critical for cleaning, preprocessing, and analyzing the data to develop predictive models. The folder includes:

- **`diabetic_data.csv`**: The main dataset containing medical records of diabetic patients, which includes numerous features such as demographic information, medical history, and hospital encounters.
- **`IDS_mapping.csv`**: A mapping file for identifying different variables and their relationships in the dataset.
- **`glossary.pdf`**: A glossary document that describes the variables used in the dataset, including their types, possible values, and missing information.

## Files in this Directory

### `diabetic_data.csv`
This dataset contains medical information for over 100,000 diabetic patients. Each row corresponds to a hospital encounter with various features related to the patient’s demographic, medical conditions, and treatments. The features include:

- **Patient information**: age, gender, race, and other demographic information.
- **Medical records**: data related to hospital admissions, medical specialties, diagnostic codes (ICD-9), lab procedures, and medications administered.
- **Readmission data**: whether the patient was readmitted to the hospital within 30 days, which serves as the target variable for the predictive model.

### `IDS_mapping.csv`
This file serves as a reference for understanding and mapping certain feature identifiers used in the `diabetic_data.csv`. It contains a structured mapping of categorical variables like race, diagnosis codes, and medical specialties to their respective values.

### `glossary.pdf`
The glossary provides detailed descriptions of the features in the `diabetic_data.csv`, including:

- **Feature names**: such as `age`, `race`, `num_lab_procedures`, `readmitted`, etc.
- **Feature roles**: indicating whether the feature is categorical, continuous, or a target variable.
- **Missing values**: Whether or not each feature contains missing values.
- **Possible values**: For categorical features like race or medical specialty.

## How to Use the Data

1. **Data Preprocessing**:
   - Load the dataset `diabetic_data.csv` using Pandas in Python.
   - Perform necessary data cleaning, including handling missing values, converting categorical features, and creating the target variable for prediction.

2. **Variable Mapping**:
   - Use the `IDS_mapping.csv` file to correctly interpret the categorical variables and their values in `diabetic_data.csv`.

3. **Reference the Glossary**:
   - Use the `glossary.pdf` document to understand the role of each feature, the possible values, and how to handle missing data.

4. **Model Building**:
   - Once the data is cleaned and preprocessed, use it to train machine learning models for predicting patient readmission.

## Conclusion
The **Data** folder provides all necessary files for preprocessing, understanding, and using the dataset to build predictive models for diabetes readmission. Proper handling of the features and missing values is essential for model accuracy.
