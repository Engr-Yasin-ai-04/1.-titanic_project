# 🚢 Titanic Survival Prediction - Machine Learning Project

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2-green.svg)](https://www.djangoproject.com/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A complete Machine Learning web application that predicts passenger survival on the Titanic using various ML algorithms. Built with Django and deployed with a beautiful user interface.

## 📊 Project Overview

This project uses the classic Titanic dataset to predict whether a passenger survived the Titanic disaster based on features like:
- Age
- Gender
- Passenger Class
- Fare
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Embarkation port

The application provides an interactive web interface where users can input passenger details and get real-time survival predictions.

## 🎯 Features

- ✅ **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features
- ✅ **Multiple ML Models**: Implements various algorithms including Logistic Regression, Random Forest, SVM, and Decision Trees
- ✅ **Model Persistence**: Saves trained model using pickle for efficient predictions
- ✅ **Interactive Web Interface**: User-friendly form to input passenger details
- ✅ **Real-time Predictions**: Instant survival predictions with probability scores
- ✅ **Model Evaluation**: Displays accuracy, precision, recall, and confusion matrix
- ✅ **Responsive Design**: Works on desktop and mobile devices

## 🏗️ Project Structure

titanic_project/
├── manage.py
├── db.sqlite3
├── requirements.txt
├── data/
│ └── train.csv # Titanic training dataset
├── predictor/
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py # Database models
│ ├── views.py # Web views and logic
│ ├── urls.py # URL routing
│ ├── ml_model.py # ML model training and prediction
│ ├── forms.py # Django forms
│ ├── titanic_model.pkl # Saved trained model
│ ├── static/ # Static files (CSS, JS)
│ └── templates/
│ └── predictor/
│ └── index.html # Main application interface
└── titanic_project/
├── init.py
├── settings.py # Django project settings
├── urls.py # Main URL configuration
├── asgi.py
└── wsgi.py


## 📸 Screenshots

| GUI Interface | Feature Selection | Prediction Result |
|---------------|-------------------|-------------------|
| ![GUI Interface](1_Output_GUI.JPG) | ![Feature Selection](1_Output_Selection.JPG) | ![Prediction Result](2_Output_Program.JPG) |

## 🚀 Installation & Setup

### Prerequisites

- Python 3.9 or higher
- pip package manager
- Git (optional)

### Step-by-Step Installation

1. **Clone the repository**
```bash
git clone https://github.com/Engr-Yasin-ai-04/titanic-survival-prediction.git
cd titanic-survival-prediction
