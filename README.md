# Breast Cancer Prediction using Machine Learning
# Problem Statement
To develop a Machine Learning model that predicts whether a breast tumor is benign or malignant for early cancer detection.

# Overview
This project uses Machine Learning techniques to predict breast cancer using medical diagnostic data. The dataset is analyzed and preprocessed before training the models. Logistic Regression and K-Nearest Neighbors (KNN) algorithms are used for classification. The system helps in identifying whether a tumor is benign or malignant with good accuracy.

# Dataset Information
Important Features:
Radius,
Texture,
Perimeter,
Area,
Concavity,
Concave Points,
Symmetry,
Fractal Dimension.
## Target Variable:
M → Malignant,
B → Benign
## Technologies Used
Python,
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scikit-learn,


# Methods
Methods
## 1. Data Preprocessing
 - Handling missing values
 - Encoding categorical labels
 - Feature selection
 - Feature scaling using StandardScaler

## 2. Exploratory Data Analysis (EDA)
 - Correlation heatmap
 - Feature distribution analysis
 - Boxplots and visualizations

## 3. Model Training
Two Machine Learning models were trained:
1.Logistic Regression
 - Used for binary classification
 - Predicts probability of cancer
2.K-Nearest Neighbors (KNN)
 - Distance-based classification algorithm
 - Classifies based on nearest neighbors
 
## 4. Model Evaluation
- Performance evaluated using:
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

# key Insights
- Logistic Regression improved malignant tumor detection recall from 86% (KNN) to 95%, reducing missed cancer cases from 6 patients to 2 patients.  
- The balanced Logistic Regression model achieved 97.37% accuracy, improving overall prediction performance compared to 93.86% accuracy in KNN.
- Feature scaling and hyperparameter tuning improved KNN classification performance, achieving 96.92% cross-validation accuracy.
- ROC-AUC scores of 0.996 (Logistic Regression) and 0.9825 (KNN) showed excellent tumor classification capability for early breast cancer detection.
# Results & Conclusion
The project successfully implemented Logistic Regression and KNN models for breast cancer prediction. Logistic Regression achieved the best performance with 97.37% accuracy and reduced missed malignant cases from 6 to 2. Data preprocessing, feature scaling, cross-validation, and ROC-AUC analysis improved model reliability for early cancer detection.

# Future Work
- Deep Learning implementation
- Streamlit deployment
- Real-time prediction system
