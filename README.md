# Pass_Fail_Predictor

## Overview 
Built a supervised classification model that predicts whether a student is likely to pass or fail based on two behavioral features: Study Hours and Sleep Hours. This project demonstrates the practical application of logistic regression, feature scaling, and model evaluation in a minimal yet insightful dataset. Aimed at showcasing how simple input features can still yield valuable predictive insights.

## 🧰 Tech Stack: 

Python – Core language for data preprocessing and model training
NumPy & Pandas – Used for efficient data manipulation and analysis
Seaborn – Enabled clear and informative data visualizations
Scikit-learn – Applied logistic regression, feature scaling, and model evaluation techniques

## 🧩 System Architecture: 
1. Data Collection → 2. Preprocessing → 3. Model Training → 4. Evaluation & Visualization

Data Collection: Small structured dataset consisting of two features: study hours and sleep hours per student, with a binary output (Pass/Fail).

Preprocessing: Cleaned and scaled features using StandardScaler to normalize input values and improve model performance.

Model Training: Employed logistic regression with class weights set to balanced to handle potential class imbalance and increase generalization.

Evaluation & Visualization: Used metrics like accuracy and visual tools (e.g., scatter plots, decision boundaries) to evaluate and interpret model predictions.



