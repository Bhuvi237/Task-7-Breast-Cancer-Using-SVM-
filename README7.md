# Breast Cancer Classification using SVM

# Overview
-This project uses the Breast Cancer dataset from kaggle to classify tumors as Malignant or Benign using Support Vector Machines (SVM).We train models with different kernels, tune hyperparameters using GridSearchCV, evaluate model performance, and visualize the decision boundary in 2D using PCA.

# Steps Implemented
1.Load Dataset – Breast cancer data from kaggle.
2.Data Preprocessing – Standardize features using StandardScaler.
3.Train-Test Split – 80% training, 20% testing.
4.Model Training – Train SVM with:
-Linear Kernel
-RBF Kernel
5.Hyperparameter Tuning – Use GridSearchCV to find optimal C and gamma.
6.Cross-Validation – Check stability of the best model.
7.Dimensionality Reduction – Apply PCA (2 components) for visualization.
8.Decision Boundary Visualization – Plot classification regions in 2D space.

# Results
Linear Kernel Accuracy: ~95%
RBF Kernel Accuracy: ~98%
Mean Cross-Validation Accuracy: ~97%

# Visualization
PCA Projection: Red and Blue regions represent Malignant & Benign classes.
Decision Boundary: Shows how the SVM separates the two classes in reduced dimensions.
