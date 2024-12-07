📋 Project Overview

This project focuses on predicting the likelihood of breast cancer using machine learning techniques based on patient data, including demographic information and medical imaging results. The primary goal is to classify tumors as malignant (cancerous) or benign (non-cancerous) to aid in early detection and prevention, ultimately improving patient outcomes.

🚀 Use Case

Early Detection and Improved Outcomes
Challenge: Breast cancer often develops without symptoms, making early detection critical.
Goal: Build a robust predictive model to identify high-risk individuals based on patient data, enabling timely intervention and better healthcare planning.

📊 Data Description

Source: Kaggle Breast Cancer Dataset
Dataset Overview:
Total records: 570
Attributes: 32 (30 predictors, 1 response variable diagnosis to classify benign or malignant cases, and 1 unique identifier).
Notable Predictors:
Tumor size (radius_mean, perimeter_mean, area_mean).
Texture and smoothness (texture_mean, smoothness_mean).
Compactness and symmetry (compactness_mean, symmetry_mean).
Target: diagnosis (malignant or benign).
🛠️ Methods and Models
Exploratory Data Analysis
Correlation Analysis: Identified features with a high correlation (e.g., perimeter_mean, concave_points_mean) using a correlation matrix and heatmaps to understand key attributes influencing predictions.
Visualization: Pair plots and heatmaps highlighted differences between benign and malignant cases.
Data Preprocessing
Data Cleaning: No missing values; no imputation required.
Standardization: Standardized features for consistent scaling.
Dimensionality Reduction: Not performed as all features contributed significantly to predictions.
Models Evaluated
Logistic Regression:

Accuracy: 98.2%
Precision: 97.7%
F1 Score: 97.7%
ROC AUC Score: 0.997
Conclusion: Best performer with balanced sensitivity and specificity.
Random Forest Classifier:

Accuracy: 96.5%
Precision: 97.6%
F1 Score: 95.2%
ROC AUC Score: 0.995
Decision Tree:

Accuracy: 96.5%
Precision: 97.6%
F1 Score: 95.2%
ROC AUC Score: 0.944
Neural Networks:

Accuracy: 96.5%
Precision: 97.6%
F1 Score: 95.2%
ROC AUC Score: 0.977

📈 Key Insights

Logistic Regression: Demonstrated the highest accuracy and interpretability, making it the preferred model for this dataset.
Random Forest and Neural Networks: Showed strong performance but slightly lower specificity than logistic regression.
Key Attributes: Features such as perimeter_mean, concave_points_mean, and radius_se were consistently important across models.

📝 How to Run the Project

Data Preprocessing:
Load data and validate the absence of missing values.
Standardize features for improved model performance.
Model Training and Testing:
Split the dataset (e.g., 70% training, 30% testing).
Train models including Logistic Regression, Random Forest, Decision Tree, and Neural Networks.
Evaluation:
Compare models using metrics like accuracy, precision, recall, F1-score, and ROC AUC.
Deployment:
Deploy the best-performing model (Logistic Regression) for real-world prediction tasks.

📌 Future Improvements

Hyperparameter Tuning: Enhance model performance through grid search or random search.
External Validation: Test the model on external datasets for generalizability.
Real-Time Application: Develop APIs or applications for real-time prediction.

👤 Authors

Raaga Sindhu Mangalagiri
