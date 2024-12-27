# Hospital Readmission Analysis (within 30 Days)

## Overview
This project analyzes patient readmission within 30 days of discharge using data from a hospital system. The goal is to identify factors contributing to readmissions and provide actionable insights for improving healthcare outcomes.

## Dataset
The analysis is based on a synthetic dataset (`train.csv`) with 25,000 records and 65 features. These features include:
- Patient demographics
- Medical history
- Medications prescribed
- Procedures performed during hospital stays

## Objectives
- Understand patterns in readmission rates.
- Identify significant predictors of readmissions.
- Build a predictive model using machine learning.

## Steps in the Analysis
1. **Data Loading and Exploration**:
   - Initial exploration of the dataset structure and summary statistics.
   - Identified features contributing to readmissions.

2. **Data Preprocessing**:
   - Conversion of categorical boolean columns into binary (0 and 1).
   - Handling missing values and normalizing numeric features.

3. **Visualization**:
   - Visualized trends in readmission rates based on key factors.
   - Correlation analysis of medical procedures and patient outcomes.

4. **Modeling**:
   - Built and evaluated a `RandomForestClassifier` to predict readmission likelihood.

5. **Results**:
   - Model achieved an accuracy of **67.5%**.
   - Identified critical features influencing readmission.

## Key Findings
- Patients with higher **number_inpatient** visits had a significantly higher probability of readmission.
- Medication adherence and age groups also played a significant role.

## Tools and Libraries
- Python
- pandas, matplotlib, seaborn
- scikit-learn
- Jupyter Notebook
