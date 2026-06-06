Heart Disease Prediction Using Machine Learning

Trained and compared 3 ML models on real patient medical data.  
Key finding: Random Forest achieved the best performance — Chest Pain Type, Max Heart Rate, and Thalassemia are the strongest predictors of heart disease.

This project builds a complete machine learning pipeline to predict the presence of heart disease using patient health indicators — from raw data cleaning to model comparison and final evaluation.

🤖 Project Features
✅ Data Loading & Inspection (shape, dtypes, nulls, duplicates)
✅ Data Cleaning & Preprocessing (duplicates removed, StandardScaler applied)
✅ Feature Engineering (correlation heatmap, Random Forest feature importance)
✅ 3 ML Models Trained (Logistic Regression, Random Forest, KNN)
✅ Model Comparison (Accuracy, Precision, Recall, F1 Score)
✅ Confusion Matrix for best model visualization

🔍 Key Findings
Random Forest** outperformed Logistic Regression and KNN across all metrics
Chest Pain Type, Max Heart Rate & Thalassemia** are the top 3 predictors
Feature scaling** with StandardScaler improved model stability and accuracy
Correlation heatmap** revealed strong links between thalach, cp, and the target
The final model supports **early heart disease risk identification** from routine health data

Technologies Used
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-Learn · Google Colab

Dataset
[Heart Disease Dataset — Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

Author
Pujari Bhanu Prasad
[GitHub](https://github.com/bhanuprasad121)
