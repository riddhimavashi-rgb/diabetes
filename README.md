# Diabetes Prediction Using Machine Learning

## Project Overview
This project compares Decision Tree and K-Nearest Neighbors (KNN)
models for diabetes classification using health-related measurements.

## Dataset
Pima Indians Diabetes Database:
https://raw.githubusercontent.com/npradaschnor/Pima-Indians-Diabetes-Dataset/master/diabetes.csv

The notebook downloads the dataset directly from this URL.

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Data Preparation
- Checked missing values.
- Treated zero values in selected medical measurement columns
  as missing values.
- Used median imputation inside training pipelines.
- Split data into 80% training and 20% testing.

## Models
- Decision Tree (maximum depth 5)
- K-Nearest Neighbors (5 neighbors)

## Results
- Decision Tree test accuracy: 75.97%
- KNN test accuracy: 75.32%
- Better by test accuracy: Decision Tree

See the notebook for confusion matrices and classification reports.

## How to Run
1. Open the notebook in Google Colab.
2. Run its code cell.
3. The dataset is loaded from the URL above.

## Conclusion
The two classifiers were compared using test accuracy and confusion
matrices. The better model by accuracy was: Decision Tree.

## Disclaimer
This is an educational project, not a medical diagnostic tool.
The dataset represents a specific population and results may not
generalize to other populations.
