# 🎓 Student Exam Performance Prediction (End-to-End ML Project)

## 🚀 Overview
This is a production-style End-to-End Machine Learning project that predicts a student's **Maths score** based on demographic and academic factors.

The project covers the complete ML lifecycle including:
- Data Ingestion
- Data Transformation
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Model Serialization
- Flask Deployment

---

## 📊 Problem Statement

Predict the **Maths score** of a student based on:
- Gender
- Race/Ethnicity
- Parental Education Level
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

## 🛠 Tech Stack

- Python 3.10
- Scikit-learn 1.3.0
- Pandas
- NumPy
- Flask
- Dill (Model Serialization)
- Logging & Custom Exception Handling
- Conda Environment Management

---

## 🏗 Project Architecture

artifact/
logs/
notebook/
src/
├── components/
├── pipeline/
├── utils.py
templates/
app.py
requirements.tx

## ⚙️ How To Run Locally

### 1️⃣ Create Environment
```bash
conda create -n mlproject python=3.10
conda activate mlproject

python app.py

## 📷 Application Preview

![Student Exam Predictor](assets/app_ui.png)
