# Credit Risk Model Validation and Performance Evaluation

# Project Overview
This project focuses on developing and implementing a comprehensive credit risk model validation framework to evaluate the predictive performance and discriminatory power of a borrower default classification model.
The analysis replicates industry-standard validation techniques used in banks and financial institutions for assessing the performance of credit scoring and Probability of Default (PD) models.
Using Python-based statistical and machine learning tools, the project evaluates model performance across multiple dimensions including discrimination, classification accuracy, ranking ability, and information efficiency.

# Objectives

Develop a framework to evaluate the predictive power of a credit risk classification model.
Implement multiple industry-standard validation metrics used in credit risk model validation.
Explore borrower score distributions to determine optimal classification cut-offs.
Assess model discriminatory power using statistical metrics widely used in banking risk analytics.

# Data & Analytical Workflow
The project worked on borrower-level credit risk data to analyse default prediction performance.

# 1. Cut-off Identification
To determine the optimal classification threshold:
Used Goods vs Bads analysis
Calculated Marginal % Goods and Marginal % Bads
Plotted Marginal Good/Bad distributions to identify the optimal score cut-off
These techniques help determine the point at which a borrower should be classified as default / non-default.

# Model Discrimination Analysis
The project implemented industry-standard discriminatory power metrics used in credit risk validation.
ROC Analysis
Receiver Operating Characteristic (ROC) Curve
Area Under Curve (ROC AUC)
These metrics evaluate how well the model separates good borrowers from bad borrowers.

# Gini Coefficient

Implemented Gini Coefficient calculation
Used as a key performance metric in credit scoring models
Kolmogorov-Smirnov (KS) Statistics
KS Plot
KS Score / KS Statistic
KS Difference Curve
KS measures the maximum separation between cumulative distributions of Goods and Bads, which is widely used in bank credit risk validation frameworks.

# Ranking Power & Portfolio Level Evaluation
To evaluate the model’s ability to rank borrowers by risk, the following techniques were implemented:
Cumulative Accuracy Profile (CAP)
CAP Curve
CAP AUC
Pietra Index
These metrics evaluate how effectively the model captures bad borrowers within the highest risk segments.

# Classification Performance Evaluation
The project implemented multiple classification diagnostics using Python and sklearn:
Confusion Matrix
Precision
Recall
F1 Score

Used sklearn Classification Report to calculate:
Precision
Recall
F1 Score
Support

# Additionally:
Implemented Confusion Matrix using rating grades
Used a direct method for confusion matrix calculation
This analysis helped evaluate the accuracy of the default classification model.

# Information Value & Statistical Divergence Analysis
To assess the information content and separation power of risk scores, the project explored:
Weight of Evidence (WoE)
Entropy
Kullback-Leibler (KL) Divergence
CIER (Conditional Information Entropy Ratio)

These statistical measures help evaluate the predictive information contained in borrower risk scores.

# Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn

# Key Outcomes
Developed a full credit risk model validation framework used to evaluate borrower default prediction models.
Implemented multiple industry-standard validation metrics used in banks and financial institutions.
Explored borrower score distributions to determine optimal risk classification thresholds.
Evaluated model discriminatory power, ranking ability, and classification performance using statistical and machine learning techniques.

# Author
Toshar Tarte
