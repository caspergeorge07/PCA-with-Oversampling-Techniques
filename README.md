**Project Title
PCA with Oversampling Techniques: Enhancing Classification in Imbalanced Datasets

**Overview
This project integrates Principal Component Analysis (PCA) with Oversampling Techniques like SMOTE to address class imbalance in datasets. By combining dimensionality reduction with synthetic sampling, the project improves model performance and enhances the classification of minority class instances.

**Objectives

Reduce dataset dimensionality using PCA, focusing on the most significant components while retaining key features.
Balance imbalanced datasets using oversampling techniques such as SMOTE and ADASYN.
Compare the performance of machine learning models with and without PCA and oversampling.
Evaluate the impact of PCA on oversampling efficiency and downstream classification.

**Workflow
Data Preprocessing:

Standardized features for consistent scaling.
Split the dataset into training and testing subsets.

Dimensionality Reduction:

Applied PCA to extract the top components explaining the majority of the variance.
Retained components that explain 90% of the total variance.

Oversampling:

Addressed class imbalance using techniques like SMOTE, ADASYN, and Random Oversampling.
Balanced the minority class to improve classifier performance.

Model Training:

Trained models such as Logistic Regression, Random Forest, and Gradient Boosting on both raw and PCA-transformed datasets.
Compared results with and without oversampling to assess improvements.
Evaluation:

Used metrics like Accuracy, Precision, Recall, F1 Score, and ROC-AUC to evaluate model performance.

**Key Results

PCA reduced dimensionality by retaining only the top components while preserving 90% of the variance.
Models trained with PCA and oversampling showed significant improvements in:
Recall for the minority class.
Overall classification metrics (F1 Score, Precision).
SMOTE proved to be the most effective oversampling method when paired with PCA.

Technologies Used
Programming: Python
Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, imbalanced-learn
Techniques: Principal Component Analysis (PCA), Synthetic Minority Oversampling (SMOTE), ADASYN, Random Oversampling
