Predictive Analysis Using Machine Learning

📌 Project Overview :

This project demonstrates predictive modeling using machine learning techniques for both classification and regression tasks.
It provides a complete end-to-end workflow:

Data preprocessing

Feature selection

Model training

Hyperparameter tuning

Model evaluation and visualization


The project includes two Jupyter notebooks:

Classification — Predicting cancer diagnosis using the Breast Cancer Wisconsin dataset.

Regression — Predicting housing prices using the California Housing dataset.


📂 Repository Structure
bash
Copy code
├── Predictive_Analysis_Classification.ipynb  # Classification notebook
├── Predictive_Analysis_Regression.ipynb      # Regression notebook
├── README.md                                 # Project description
└── .gitignore                                # Ignored files list


🛠 Features
Data Splitting — Train–test split for unbiased evaluation.

Preprocessing — Scaling numerical features with StandardScaler.

Feature Selection — Using SelectKBest with mutual_info_classif (classification) and f_regression (regression).


Models Used:

Logistic Regression (classification baseline)

Linear Regression (regression baseline)

Random Forest (alternative model for both tasks)

Hyperparameter Tuning — Using GridSearchCV for model optimization.


Evaluation Metrics:

Classification → Accuracy, Precision, Recall, F1, ROC AUC, Confusion Matrix, ROC Curves

Regression → MAE, RMSE, R², Feature Importance

Visualizations — Feature scores, importance charts, and ROC curves.

📊 Datasets Used
Breast Cancer Wisconsin (Diagnostic) — from sklearn.datasets.load_breast_cancer

California Housing — from sklearn.datasets.fetch_california_housing

📦 Requirements
Install dependencies before running the notebooks:

bash
Copy code
pip install numpy pandas matplotlib scikit-learn


📜 License
This project is licensed under the MIT License — you are free to use, modify, and distribute it with proper attribution.
