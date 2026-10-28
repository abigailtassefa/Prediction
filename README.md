

---

## Project Overview

**Prediction** is a web-based machine learning application built with Django that estimates real estate market prices based on core property attributes. The system uses a linear regression model trained on standardized feature inputs to generate quick, automated house price estimates through a clean user interface.

---

## Key Features

* **Machine Learning Pipeline:** Trains a scikit-learn Linear Regression model using feature scaling (`StandardScaler`) to process continuous variables like property size and age alongside discrete feature counts (bedrooms).
* **Interactive Web Interface:** Simple Django web form allowing users to input house details (square footage, number of bedrooms, and age) and receive real-time price predictions.
* **Model Persistence:** Serializes trained model weights and feature scalers using `joblib` for persistent storage and low-latency inference during web requests.
* **RESTful Architecture:** Modular Django project layout separating full-stack view controllers, URL routing, model logic, and static templating.

---

## Tech Stack & Tools

* **Backend Framework:** Django 4.2
* **Machine Learning & Data Processing:** scikit-learn, NumPy, Pandas
* **Model Serialization:** Joblib
* **Database:** SQLite3
* **Language:** Python 3.12
