This repository contains a machine learning project for predicting diabetes based on health metrics using the SVM (Support Vector Machine) algorithm with a linear kernel.

### Dataset
The dataset `diabetes.csv` contains several health metrics (like glucose levels, blood pressure, BMI, etc.) and a binary outcome indicating diabetes presence (1) or absence (0).

### Data Preprocessing
- **Standardization**: Features are standardized using `StandardScaler` from `sklearn.preprocessing` to scale features to a standard normal distribution.

### Model Training
- **Support Vector Machine (SVM)**: Utilizes SVM with a linear kernel (`svm.SVC(kernel='linear')`) for binary classification. SVM is chosen for its effectiveness in separating data points in high-dimensional spaces.

### Evaluation
- **Performance Metrics**: Model performance is evaluated using accuracy score and confusion matrix to assess its predictive capability.

### Predictive System
- **Real-time Prediction**: Implemented in the notebook (`diabetes_prediction.ipynb`), allowing users to input new health metrics and obtain predictions on whether the person is likely to have diabetes.
