# Random_Forest_RealTime_BreastCancer-
Random Forest (Machine Learning) — Real-Time Example
Use case: Predict whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset (a real-world dataset bundled with scikit-learn).
Random Forest is a strong baseline for many classification problems. We evaluated with accuracy, precision, recall, F1, and ROC/AUC. We interpreted feature importance to understand model drivers. We improved performance using GridSearchCV.
What you'll learn
What Random Forest is and how it works (bagging + random feature selection).
Load & understand a real dataset.
Train/Test split and baseline model.
Model evaluation (accuracy, precision, recall, F1, confusion matrix).
ROC Curve & AUC.
Feature importance interpretation.
Hyperparameter tuning with GridSearchCV.
Make a prediction for a new patient.
1) What is Random Forest? (Theory — short)
Ensemble of decision trees trained on bootstrap samples (bagging).
At each split, it considers a random subset of features, reducing correlation between trees.
The final prediction is by majority vote (classification) or average (regression).
Why it works well

Handles non-linear relationships & feature interactions automatically.
Robust to outliers and missing scaling.
Usually strong performance with minimal tuning.
Key hyperparameters

n_estimators: number of trees.
max_depth, min_samples_split, min_samples_leaf: control tree complexity.
max_features: number of features considered at each split.
