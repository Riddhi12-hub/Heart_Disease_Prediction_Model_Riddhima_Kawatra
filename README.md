Overview

This project predicts whether a person has heart disease using machine learning models trained on the Heart Disease 2020 Cleaned Dataset. The objective is to analyze health and lifestyle factors and build an optimized predictive model.

📊 Dataset

Total Records: 319,795

Total Features: 18

Target Variable: HeartDisease (Yes/No)

The dataset contains demographic, lifestyle, and medical information such as BMI, smoking, age category, physical health, mental health, etc.

🔎 Steps Performed

Data cleaning and preprocessing

One-Hot Encoding for categorical features

Train-test split (80-20, stratified)

Model training and comparison

Hyperparameter tuning using GridSearchCV

Evaluation using Precision, Recall, F1-score, ROC-AUC

Since the dataset is imbalanced, F1-score was prioritized over accuracy.

🤖 Models Used

Logistic Regression

K-Nearest Neighbors

Random Forest (Best Performing Model)

📈 Results

The optimized Random Forest model achieved the best performance in terms of F1-score and ROC-AUC.
Class imbalance was handled using class_weight="balanced".

🛠️ Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

🚀 Conclusion

Machine learning can effectively predict heart disease using health-related features. Proper preprocessing and evaluation metrics are crucial for handling imbalanced datasets.
