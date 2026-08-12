# Railway Failure Type Prediction

## Project Overview

This project predicts the **type of railway failure** using machine learning based on railway operational, environmental, and equipment-related features.

The project includes the complete machine learning workflow, starting from data cleaning and preprocessing to model training, evaluation, and deployment using Streamlit.

## Problem Statement

Railway systems can experience different types of failures due to factors such as train conditions, environmental conditions, track conditions, and equipment wear.

The objective of this project is to build a machine learning classification model that can predict the **failure type** from the available railway data.

## Project Workflow

- Data Collection
- Data Cleaning
- Data Preprocessing
- Feature Preparation
- Model Training
- Model Evaluation
- Model Selection
- Streamlit Deployment

## Machine Learning Models

The following classification models were developed and compared:

- Logistic Regression
- Decision Tree
- Random Forest

The models were evaluated to identify the most suitable model for predicting railway failure types.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- Jupyter Notebook

## Dataset

The dataset contains railway-related operational, environmental, and equipment features such as:

- Region
- Season
- Train Type
- Train Age
- Average Speed
- Distance Travelled
- Ambient Temperature
- Humidity
- Rainfall
- Wheel Wear
- Track Vibration
- Rail Wear
- Bearing Temperature
- Axle Temperature
- Brake Pad Wear

The target variable represents the **railway failure type**.

## Data Preparation

The dataset was prepared before model training by performing:

- Missing value handling
- Data cleaning
- Data preprocessing
- Feature transformation
- Preparation of data for machine learning models

## Streamlit Application

The trained models were integrated into a Streamlit web application.

The application allows users to enter railway-related parameters and select a machine learning model to predict the railway failure type.

### Live Application

👉 [Railway Failure Type Prediction](https://railway-failure-type-prediction-kkzgrgvhh5gqyfwpbrmc8l.streamlit.app/)

## Project Structure

```text
Railway-Failure-Type-Prediction/
│
├── Railway_Failure_Prediction_App/
│   ├── app.py
│   ├── lr.pkl
│   ├── dt.pkl
│   ├── rf.pkl
│   └── requirements.txt
│
├── Railway_Failure_Prediction_ML/
│
├── LICENSE
└── README.md
