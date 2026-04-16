🎯 Student Performance Indicator

A Machine Learning project that predicts student performance based on various academic and demographic features. This project demonstrates an end-to-end ML pipeline including data ingestion, transformation, model training, and deployment using a web interface.

🚀 Project Overview

The goal of this project is to analyze student data and predict their performance using machine learning algorithms. It helps in identifying key factors affecting student scores.

🧠 Features
End-to-end Machine Learning pipeline
Data Ingestion, Transformation, and Model Training
Model evaluation and selection
Web-based prediction interface (Flask)
Modular and scalable code structure
Logging and exception handling

📁 Project Structure
mlproject-main/
│
├── artifacts/              # Saved models and datasets
├── notebook/               # Jupyter notebooks (EDA & training)
├── src/
│   ├── components/         # Core ML pipeline components
│   ├── pipeline/           # Training & prediction pipelines
│   ├── utils.py            # Utility functions
│   ├── logger.py           # Logging
│   └── exception.py        # Custom exception handling
│
├── templates/              # HTML templates (UI)
├── app.py                  # Flask application
├── requirements.txt        # Dependencies
├── setup.py                # Package setup
└── README.md               # Project documentation

⚙️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
CatBoost / XGBoost
Flask
HTML/CSS

🔄 ML Pipeline
Data Ingestion
Reads raw dataset
Splits into train/test
Data Transformation
Handles missing values
Encoding categorical features
Feature scaling
Model Training
Trains multiple models
Selects best-performing model
Prediction Pipeline
Loads trained model
Takes user input via UI
Outputs prediction

📊 Dataset Features
Gender
Race/Ethnicity
Parental Level of Education
Lunch Type
Test Preparation Course
Reading Score
Writing Score

📈 Model Performance
Multiple models evaluated (Linear Regression, Random Forest, CatBoost, etc.)
Best model selected based on accuracy metrics

🧪 Notebooks
EDA Notebook → Data analysis and visualization
Model Training Notebook → Model experiments

🔐 Logging & Exception Handling
Custom logging implemented for debugging
Centralized exception handling for robustness

📌 Future Improvements
Deploy on AWS / Azure
Add real-time data input
Improve UI/UX
Add more advanced models