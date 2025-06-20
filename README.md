## End to End ML project
# 📊 Student Performance Prediction - End-to-End ML Project

This repository contains an **industry-style machine learning project** built to predict students' academic performance based on various factors like study hours, parental education, lunch type, and test preparation.

The main goal was to **simulate a real-world ML workflow** — including structured coding, modular pipeline implementation, model selection/tuning, and deployment — with a strong focus on writing clean, production-level code.

---

## 📌 Key Features

- ✅ **Project structure** following best practices (modular, reusable code)
- ✅ **Exception handling** and **custom logging** for traceability
- ✅ **EDA & data preprocessing** using Scikit-learn pipelines
- ✅ **Model training** and **evaluation** with multiple algorithms
- ✅ **GridSearchCV-based hyperparameter tuning**
- ✅ **Prediction pipeline** to handle future input
- ✅ **Flask-based API** for real-time predictions (deployment-ready)

---

## 🗂️ Project Structure

├── notebook/ # EDA notebooks and raw data
├── src/ # Core source code
│ ├── components/ # Ingestion, transformation, training
│ ├── logger.py # Custom logging
│ ├── exception.py # Custom exception handling
│ └── pipeline/ # Prediction pipeline scripts
├── artifacts/ # Saved datasets and models
├── app.py # Flask application
├── requirements.txt # Python dependencies
├── templates/ # HTML templates for Flask app
├── README.md # Project description
