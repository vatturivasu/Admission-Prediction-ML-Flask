##Admission Prediction System

Project Overview

This project is a Machine Learning-based web application that predicts the probability of a student getting admission into graduate programs based on academic performance and profile details.

The main objective of this project is to help students understand their chances of admission by analyzing important factors such as GRE score, TOEFL score, CGPA, and research experience. The system uses a regression model trained on historical data to generate predictions.

A simple web interface is developed using Flask to allow users to input their details and get results instantly.

Problem Statement

Many students are unsure about their chances of getting admission into universities. This project provides a data-driven approach to estimate admission probability, helping students make better decisions.

Tech Stack

- Programming Language: Python
- Framework: Flask
- Libraries: NumPy, Pandas, Scikit-learn
- Frontend: HTML, CSS
- Model: Linear Regression

Features

- Predicts admission probability based on user input
- Considers multiple parameters such as GRE, TOEFL, CGPA, SOP, LOR, and research
- Simple and user-friendly interface
- Real-time prediction using trained model

Project Structure

Admission-Prediction/
│── Admission_Prediction.csv
│── Linear Regression.ipynb
│── app.py
│── templates/
│── static/
│── README.md

Workflow

1. Data collection from dataset
2. Data preprocessing and cleaning
3. Exploratory Data Analysis
4. Model training using Linear Regression
5. Model evaluation
6. Deployment using Flask

Model Details

- Algorithm: Linear Regression
- Type: Regression problem
- Output: Admission probability (range between 0 and 1)

How to Run the Project

Clone the repository:

git clone https://github.com/vatturivasu/Admission-Prediction-.git

Navigate to the project folder:

cd Admission-Prediction-

Install dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Open the browser and go to:

http://127.0.0.1:5000/

Live Demo

https://admission-prediction-production-5c8d.up.railway.app

Future Improvements

- Implement advanced models such as Random Forest or XGBoost
- Improve UI design
- Add user authentication
- Deploy using cloud platforms

Author

Vasu V
https://github.com/vatturivasu

Acknowledgements

The dataset used in this project is based on publicly available graduate admission datasets.