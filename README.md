# Heart-disease-detection-project
This project aims to predict whether a person is at risk of developing heart disease based on various medical parameters.
Using machine learning models, we analyze patient data and classify them as "at risk" or "not at risk" for heart disease.
The goal is to assist healthcare professionals in early detection and better decision-making.
Predict heart disease risk with machine learning models.
Clean and preprocess real-world medical datasets.
Perform exploratory data analysis (EDA) to understand key factors influencing heart health.
Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
Interactive dashboard (optional if you built it) using Streamlit/Flask for easy predictions.
We generally used different types of technology like: Technologies Used like:
Python
Scikit-learn
Pandas
NumPy
Matplotlib / Seaborn (for data visualization)
Streamlit / Flask (for web app deployment, if done)
DataSet used in this project:Dataset
Source: UCI Heart Disease Dataset
Age, Sex, Chest Pain Type (cp)Resting Blood Pressure (trestbps), Serum Cholesterol (chol), Fasting Blood Sugar (fbs), Maximum Heart Rate Achieved (thalach), Exercise Induced Angina (exang)ST depression (oldpeak) etc.
It generally works:
Load the heart disease dataset.
Clean data: handle missing values, encode categorical variables, and scale numerical features.
Split dataset into training and testing sets.
Train multiple machine learning models (Logistic Regression, Random Forest, KNN, SVM, etc.).
Evaluate model performance using classification metrics.
(Optional) Deploy the best model with a web app for real-time prediction.
It gives resuls:
Best Model: Random Forest Classifier
Test Accuracy: 88%
ROC-AUC Score: 0.91
Precision: 0.87, Recall: 0.89.
Higher age and presence of chest pain are strong indicators of heart disease risk.
Exercise-induced angina and maximum heart rate achieved are highly correlated with target variable.
Certain features (like fasting blood sugar) have weaker correlation and can be dropped for better model performance.
Example plots:
Correlation heatmaps
Distribution plots for major features
ROC Curve plots for models
