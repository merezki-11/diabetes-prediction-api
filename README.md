**🩺 GlucoGuard AI: Diabetes Prediction System**

Live Demo: [https://lovable.dev/projects/6d582691-fcc5-4568-8750-494443afb6b1]

API Endpoint: https://diabetes-prediction-api-merezki.onrender.com

**Overview**
GlucoGuard AI is a full-stack Machine Learning application designed to predict the likelihood of
diabetes based on clinical parameters. It bridges the gap between data science and user-centric
design by connecting a Random Forest model to a high-end React dashboard.

**Technical Stack**
- Frontend: React, Tailwind CSS
- Backend: FastAPI (Python)
- Machine Learning: Scikit-learn, Random Forest Classifier
- Deployment: Render (API) and GitHub

**Model Performance**
- Algorithm: Random Forest (Optimized via GridSearchCV)
- Dataset: Pima Indians Diabetes Database
-  Accuracy: ~78-80% on test data

**Architecture**
The system uses a decoupled architecture:

1. Frontend sends a JSON POST request to the cloud-hosted API.
2. API (FastAPI) processes the input using a saved StandardScaler and RandomForest model.
3. Inference is returned to the UI in real-time.

**Repository Structure**
- main.py: FastAPI application logic.
- diabetes_model.pkl: The trained Random Forest model.
- scaler.pkl: The fitted scaler for data normalization.
- requirements.txt: Python dependencies for the cloud environment.
  
