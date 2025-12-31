Heart Disease Prediction using KNN
 Project Overview
This project predicts whether a person has heart disease using the K-Nearest Neighbors (KNN) machine learning algorithm.
It focuses on essential data analysis, key visualizations, and model evaluation using a real-world healthcare dataset.
 Dataset
Source: Kaggle – Heart Disease UCI
Link: https://www.kaggle.com/datasets/ronitf/heart-disease-uci
File: heart.csv
Records: 303
Target Column: target
1 → Heart Disease
0 → No Heart Disease
 Tools Used
Python
Pandas
Matplotlib
Seaborn
Scikit-learn
 Data Preparation
Removed duplicate records
Verified absence of missing values
Standardized numerical features for better model performance
 Key Visualizations
 Heart Disease vs Non-Disease Distribution
This visualization shows the number of patients with and without heart disease.
Insight:
The dataset is fairly balanced, making it suitable for classification modeling.
 Feature Correlation Heatmap
This visualization displays the correlation between different medical attributes and heart disease.
Insight:
Chest pain type, maximum heart rate, and ST depression show strong relationships with heart disease, indicating their importance in prediction.
 Machine Learning Model
Algorithm: K-Nearest Neighbors (KNN)
Distance Metric: Euclidean
K Value: 5
 Model Performance
Accuracy: 87%
Balanced precision and recall
Correctly classified most patient records
 Key Takeaways
Simple visualizations help understand the dataset quickly
Feature scaling significantly improves KNN performance
KNN is effective for binary medical classification problems
