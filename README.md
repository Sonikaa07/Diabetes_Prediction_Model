🩺 Diabetes Prediction Project

This project uses machine learning & deep learning to predict whether a person has diabetes based on health and lifestyle factors.

🔍 Objective

Build a model that predicts diabetes (Yes/No) using features like glucose, HbA1c, BMI, activity level, smoking status, and more.

📂 Dataset

File: diabetes_dataset.csv

Target: Diabetes_Diagnosis (1 = Diabetic, 0 = Non-Diabetic)

⚙️ Workflow

Data Cleaning & Encoding – handled missing values, encoded categorical features.

Balancing Classes – applied SMOTE.

Scaling – used StandardScaler.

Model – Deep Neural Network (Keras):

Dense(32, ReLU) → Dropout

Dense(16, ReLU) → Dropout

Dense(1, Sigmoid)

Evaluation – Accuracy ~85–88%, confusion matrix, classification report.

📊 Results

✅ Good accuracy and recall for diabetic prediction.
✅ Visualized confusion matrix and class distribution.

🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, TensorFlow/Keras, Matplotlib, Seaborn
