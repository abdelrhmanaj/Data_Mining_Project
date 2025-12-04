# Diabetes Prediction Project

# 📋Project Overview
A comprehensive data mining project focused on predicting diabetes risk using medical and laboratory data. This project implements machine learning classification models to identify patients as Non-Diabetic (N), Prediabetic (P), or Diabetic (Y) based on clinical parameters.

# 🎯 Project Objectives
Predictive Modeling: Develop accurate classification models for diabetes prediction

Risk Factor Analysis: Identify key clinical markers associated with diabetes

Data Insights: Explore patterns and relationships in medical data

Visual Analytics: Create comprehensive visualizations for data understanding

# 📊 Dataset Description
Features Overview
Demographic: Gender, Age, BMI

Kidney Function: Urea, Creatinine (Cr)

Glucose Control: HbA1c (3-month average)

Lipid Profile: Total Cholesterol, Triglycerides, HDL, LDL, VLDL

Target: CLASS (N=Non-Diabetic, P=Prediabetic, Y=Diabetic)

Dataset Statistics
Total Records: 1,000 patients

Features: 12 clinical parameters

Classes: 3 (N, P, Y)

Data Types: Numerical and categorical variables

# 🛠️ Technical Implementation
# Phase 1: Data Preprocessing & Exploration ✅
Data Cleaning: Handle missing values, duplicates, and data validation

Outlier Detection: IQR method, Z-score, and medical range validation

Exploratory Analysis: Distribution analysis, correlation studies

Visualization: Comprehensive plots for data understanding

# Phase 2: Feature Engineering & Modeling 🚧
## Random Forest outperforms all other models.
•	Using all features, it achieved the highest test accuracy (0.995), perfect precision (1.0), and very high recall (0.97) and F1-score (0.98).
•	Even with the strongest features only, Random Forest still performed excellently, showing its robustness.
## SVM and Decision Tree models also perform well.
•	SVM with all features achieved high precision (0.92) and recall (0.91), making it a strong choice for balanced performance.
•	Decision Tree improves slightly when using only the strongest features, achieving a test accuracy of 0.975.
## Naive Bayes and KNN show moderate performance.
•	Naive Bayes maintains consistent results with all features, but its performance drops with strong features.
•	KNN shows a slight improvement when using strong features, but its overall performance is lower than Random Forest and SVM.
## Logistic Regression performs the worst among all models.
•	Both with all features and strongest features, it has lower precision, recall, and F1-score, indicating it may not capture the complexity of the data as well as other models.


# 📈 Key Visualizations
Generated Plots:
Outlier Detection Boxplots - Identify anomalies in clinical data

Distribution Analysis - Feature distributions with outlier highlighting

Correlation Heatmap - Relationships between clinical parameters

Pairplot Analysis - Multivariate relationships by diabetes class

Class-wise Distributions - Feature patterns across different classes
