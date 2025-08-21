📊 Loan Approval Prediction using Machine Learning

This project applies machine learning classification models to predict loan approval outcomes based on customer and financial data. It demonstrates the complete pipeline of data preprocessing, model building, and evaluation.

📂 Dataset

Source: Comp loan.csv

Contains customer and financial details used to determine loan approval.

🔄 Workflow
🧹 Data Preprocessing

Removed irrelevant columns (id, Unnamed: 0)

Handled missing values

Label Encoding & Feature Scaling

Balanced data using SMOTE

🤖 Modeling

Implemented and compared multiple classification algorithms:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree

Random Forest

📈 Evaluation Metrics

Accuracy Score

Confusion Matrix

ROC-AUC & ROC Curve

Precision, Recall, F1-score

✅ Results

Models were compared based on accuracy and ROC-AUC.

Random Forest and SVM provided the best performance on this dataset.

🚀 Future Work

Hyperparameter tuning using GridSearchCV

Advanced feature engineering for better accuracy

Deployment as a web application (Flask/Streamlit)
