# Admission Prediction System

## Project Overview

This project is a Machine Learning-based web application that predicts the probability of a student getting admission into graduate programs based on academic performance and profile details.

The system is trained on historical admission data and deployed using Flask, allowing users to input their details and receive real-time predictions.

## Problem Statement

Students often lack clarity about their chances of admission. This project provides a data-driven solution to estimate admission probability using machine learning models.

## Tech Stack

* Programming Language: Python
* Framework: Flask
* Libraries: NumPy, Pandas, Scikit-learn
* Frontend: HTML, CSS
* Deployment: Railway
* Model Types: Linear Regression, Decision Tree, Random Forest

## Features

* Predicts admission probability based on user input
* Supports multiple ML models for comparison
* Displays real-time prediction results
* Shows model-wise outputs for transparency
* Fully deployed web application

## Model Performance

The models were trained on 400 records from the dataset and evaluated using standard regression metrics.

### Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Evaluation Metrics

| Model             | R² Score | MAE   | RMSE  |
| ----------------- | -------- | ----- | ----- |
| Linear Regression | ~0.80    | ~0.04 | ~0.06 |
| Decision Tree     | ~0.75    | ~0.05 | ~0.07 |
| Random Forest     | ~0.82    | ~0.03 | ~0.05 |

Note: Values are approximate and may vary slightly depending on train-test split.

### Sample Prediction Output

* Linear Regression: 73.08%
* Decision Tree: 73.70%
* Random Forest: 73.44%

Final predicted admission chance: ~73.40%

## Workflow

1. Data collection from dataset
2. Data preprocessing and feature scaling
3. Exploratory Data Analysis
4. Model training using multiple algorithms
5. Model evaluation using R², MAE, RMSE
6. Model serialization and saving
7. Deployment using Flask and Railway

## Project Structure

Admission-Prediction/
│── Admission_Prediction.csv
│── Linear Regression.ipynb
│── app.py
│── templates/
│── static/
│── model.pkl
│── scaler.pkl
│── README.md

## How to Run the Project

git clone https://github.com/vatturivasu/Admission-Prediction-.git

cd Admission-Prediction-

pip install -r requirements.txt

python app.py

Open in browser:
http://127.0.0.1:5000/

## Live Demo

https://admission-prediction-production-5c8d.up.railway.app

## Deployment Details

* Platform: Railway
* Backend: Flask API
* Model loaded using pickle
* Scaler applied before prediction
* Handles real-time user input

## Future Improvements

* Add more advanced models (XGBoost, Gradient Boosting)
* Improve UI/UX design
* Add dataset upload feature
* Implement user authentication
* Add model explainability (SHAP/feature importance)

## Author

Vasu V
https://github.com/vatturivasu

## Acknowledgements

Dataset based on publicly available graduate admission datasets.
