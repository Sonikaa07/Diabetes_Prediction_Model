🩺 Diabetes Prediction Project

A machine learning and deep learning project to predict whether a person is diabetic or not using medical and lifestyle data.

📌 Objective

The objective of this project is to develop a predictive model that classifies patients as:

1 → Diabetic

0 → Non-Diabetic

This can assist in early detection and preventive healthcare.

📂 Dataset

File: diabetes_dataset.csv

Features Used:

Medical: Fasting Blood Glucose, HbA1c, BMI, Blood Pressure

Lifestyle: Smoking Status, Alcohol Consumption, Physical Activity Level

Demographics: Age, Sex, Ethnicity

Target Variable: Diabetes_Diagnosis

⚙️ Methodology
1. Data Preparation

Checked for missing values and handled them.

Encoded categorical features (Sex, Ethnicity, Smoking, etc.).

Created target label using medical thresholds (Glucose ≥126 or HbA1c ≥6.5).

2. Data Balancing & Scaling

Applied SMOTE to balance diabetic vs. non-diabetic cases.

Standardized features using StandardScaler.

3. Model Development

Implemented a Deep Neural Network with the following structure:

Dense(32, ReLU) → Dropout(0.3)

Dense(16, ReLU) → Dropout(0.3)

Dense(1, Sigmoid)

Optimizer: Adam

Loss Function: Binary Crossentropy

4. Model Evaluation

Test Accuracy: 85–88%

Metrics: Precision, Recall, F1-Score, Confusion Matrix

Visualization: Class distribution and confusion matrix heatmap

📊 Results

Model achieved strong accuracy and recall for diabetic patients.

Confusion matrix showed effective classification of both classes.

Demonstrated the effectiveness of ML in healthcare prediction tasks.

🚀 Future Enhancements

Experiment with additional algorithms (Random Forest, XGBoost, SVM).

Hyperparameter tuning for further accuracy improvements.

Deploy as a web application (Flask/Streamlit/Django) for real-time usage.

🛠 Tech Stack

Programming Language: Python

Libraries & Tools: Pandas, NumPy, Scikit-learn, Imbalanced-learn, TensorFlow/Keras, Matplotlib, Seaborn
