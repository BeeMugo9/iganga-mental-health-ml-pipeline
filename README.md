# iganga-mental-health-ml-pipeline
Machine learning pipeline for predicting common mental disorders using longitudinal survey data from Iganga district, Uganda
This project applies a supervised machine learning pipeline to predict the presence of common mental disorders (anxiety and depression) among individuals in the Iganga district of eastern Uganda, using data from a three-wave longitudinal mental health survey.
The analysis covers the full ML pipeline including data preprocessing, exploratory data analysis, model training (Logistic Regression, Random Forest, Gradient Boosting, and SVM), evaluation using accuracy, precision, recall, F1-score, ROC-AUC, and 5-fold stratified cross-validation.
Key findings show that SVM achieved the best balance between precision and recall (F1 = 0.39), while age, household size, and functional impairment emerged as the most important predictors from the Random Forest feature importance analysis.
Dataset: Merged longitudinal survey data from Iganga district, eastern Uganda.
Tools: Python, scikit-learn, pandas, matplotlib, seaborn.
