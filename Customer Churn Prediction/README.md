**Customer Churn Prediction using Machine Learning**

Overview

This project predicts whether a bank customer is likely to leave the bank (Exited = 1) or remain a customer (Exited = 0) using Machine Learning.

The project follows a complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model comparison, hyperparameter tuning, and Kaggle submission.



Problem Statement

Customer churn is a major challenge for banks. The objective of this project is to build a machine learning model that can accurately predict whether a customer will leave the bank based on their demographic and financial information.



 Dataset

- **Source:** Kaggle - Bank Customer Churn Prediction Competition
- **Problem Type:** Binary Classification
- **Target Variable:** Exited


 Project Workflow

- Import Libraries
- Load Dataset
- Exploratory Data Analysis (EDA)
- Missing Value Analysis
- Feature Selection
- One-Hot Encoding
- Train-Validation Split
- Feature Scaling (for applicable algorithms)
- Model Training
- Model Evaluation
- Hyperparameter Tuning using GridSearchCV
- Final Kaggle Submission



 Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier



 Model Evaluation

The following metrics were used to compare model performance:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report


Hyperparameter Tuning

Random Forest was optimized using **GridSearchCV** to find the best combination of hyperparameters.


Best Model

Random Forest Classifier (GridSearchCV Tuned)**

The final model was trained on the complete training dataset and probability predictions were generated using `predict_proba()` for Kaggle submission.



Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook





 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Classification Algorithms
- Model Comparison
- Hyperparameter Tuning
- Kaggle Competition Workflow



 Future Improvements

- Support Vector Machine (SVM)
- XGBoost
- LightGBM
- CatBoost
- Feature Engineering
- Cross Validation
- Class Imbalance Handling (SMOTE)


Author

M. Charan Sidhvi

Aspiring Machine Learning Engineer

GitHub: https://github.com/charansidhviml



⭐ If you found this project helpful, please consider giving it a star!
