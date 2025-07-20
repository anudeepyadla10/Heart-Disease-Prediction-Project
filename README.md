 Heart Disease Prediction using Python

This project aims to predict the presence of heart disease in patients using supervised machine learning algorithms. It involves detailed exploratory data analysis (EDA), data preprocessing, and model evaluation, making it a great example of data analysis with Python combined with machine learning.


 📌 Objective

To analyze medical data and build machine learning models that can accurately classify whether a patient has heart disease or not.


 🧰 Tools & Technologies Used

- Programming Language: Python  
- Libraries:
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning models and preprocessing
  - `xgboost` – Boosting algorithm
  - `tensorflow` / `keras` – Basic neural network



📊 Dataset Overview

The dataset contains several medical attributes for patients and a binary target variable:
- Features: `age`, `sex`, `cp` (chest pain), `chol`, `thalach`, `fbs`, `exang`, `slope`, `ca`, `thal`, etc.
- Target: `1` = heart disease present, `0` = no heart disease



🔍 Exploratory Data Analysis (EDA)

- Checked for missing values, data types, and outliers
- Visualized feature distributions using bar charts, histograms, and count plots
- Analyzed correlation between features and the target variable
- Found that features like chest pain type, thalassemia, and maximum heart rate are strongly related to heart disease presence



🧠 Machine Learning Models Implemented

Eight different classification algorithms were trained and tested:

1. Logistic Regression  
2. Naive Bayes  
3. Support Vector Machine (SVM)  
4. K-Nearest Neighbors (KNN)  
5. Decision Tree  
6. Random Forest  
7. XGBoost  
8. Neural Network (basic model using Keras)


✅ Best Result

Random Forest model performed best with an accuracy of 95%

