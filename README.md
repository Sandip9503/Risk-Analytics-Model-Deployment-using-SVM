# 🛡️ Risk Analytics using SVM – End-to-End ML Deployment

This project focuses on building and deploying a machine learning model to assess risk using various classification algorithms, with special emphasis on **Support Vector Machine (SVM)**. The project includes full data preprocessing, model training, evaluation, deployment pipeline, and API integration.

## 📌 Problem Statement

Predict potential risk outcomes based on input features using machine learning. The solution aims to aid businesses in making informed decisions for risk management.

## 🧰 Tools & Technologies

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Joblib
- Flask / FastAPI (for API creation)
- Docker (for containerization)
- Streamlit / Gradio *(optional UI)*

## 🧪 Workflow Overview

1. **Data Loading & EDA** – Understand dataset structure, distributions, and correlations.
2. **Preprocessing** – Missing value treatment, encoding, feature engineering, normalization.
3. **Modeling** – Logistic Regression, KNN, and SVM.
4. **Evaluation** – Accuracy, Precision, Recall, F1 Score, AUC-ROC.
5. **Hyperparameter Tuning** – Improve performance of the best model.
6. **Deployment**  
    - Save model, scaler, encoders using `joblib`
    - Create inference pipeline
    - Build API for predictions
    - *(Optional)* Build a UI using Streamlit/Gradio
    - Containerize with Docker

## 🚀 Deployment Steps

- Save final model and pre-processing tools using `joblib`
- Define a custom inference function to process new data and return predictions
- Create REST API endpoint to accept inputs and serve predictions
- Package everything into a Docker container for portability


## 📈 Results

- Best model: **SVM (Support Vector Machine)**
- Achieved strong classification performance across multiple metrics (e.g., F1-score, AUC)
- Full deployment pipeline created for real-world usability
