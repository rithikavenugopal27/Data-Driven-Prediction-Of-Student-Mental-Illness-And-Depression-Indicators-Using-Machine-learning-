# Data-Driven-Prediction-Of-Student-Mental-Illness-And-Depression-Indicators-Using-Machine-learning-
Data Driven Prediction of Student Mental Illness and Depression Indicators Using Machine Learning. 
Overview:

This project predicts student mental illness and depression indicators using machine learning techniques. Student mental health has become a major concern due to increasing academic pressure, lifestyle changes, and social stress. Our work aims to support early detection of depression by building predictive models that can help improve student well-being and academic performance.

Objective:

Predict depression among students using machine learning
Analyze factors influencing student mental health
Enable early detection and timely intervention
Identify the best-performing model for accurate prediction

Dataset:

Source: Kaggle
Size: 27,870 student records
Features: 18 attributes including demographic, academic, lifestyle, and psychological variables
Target Variable: Depression

Preprocessing:

Performed data preprocessing and exploratory data analysis
Removed outliers using the IQR method
Improved data quality and model stability

EDA Highlights:

Academic pressure showed the highest positive correlation with depression (0.47)
Younger students were more likely to experience depression
Increased work/study hours slightly increased depression levels
58.5% of students in the dataset were identified as depressed

Machine Learning Models Used:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Classifier (SVC)
Decision Tree
Random Forest
Bagging
AdaBoost
Naive Bayes
Gradient Boosting
Multi-Layer Perceptron (MLP)
SGD
LightGBM
CatBoost
XGBoost

Best Model :– CatBoost

After experimenting with multiple machine learning models, CatBoost achieved the best performance:

Train-Test Split: 80-20
Accuracy: 0.8507
Precision: 0.8542
Recall: 0.8949
F1-Score: 0.8741
ROC-AUC: 0.9215
Provides effective prediction for early depression detection among students
