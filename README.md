#Mansik-Santulan-Score

# 🧠 Mental Health Signal — Student Wellness Analytics

A machine learning-powered web application that predicts a student's **mental health score (0–10)** based on lifestyle, academic, and digital habits.

The project combines a trained machine learning model with a **FastAPI backend** and a responsive **HTML/CSS/JavaScript frontend** to provide an interactive prediction experience.

> **Disclaimer:** This project is intended for educational and informational purposes only. It is not a clinical or medical assessment and should not be used as a substitute for professional mental health advice.

---

## 🚀 Project Overview

Students' daily routines, screen time, study habits, sleep, physical activity, and perceived stress can provide useful signals for understanding overall wellness.

This project uses these factors as input to a machine learning model and generates a predicted mental health score from **0 to 10**.

The application provides:

* 📝 Interactive student information form
* 📱 Digital habit analysis
* 📚 Academic and lifestyle inputs
* 😌 Stress-level input
* 🤖 Machine learning-based prediction
* 📊 Visual score representation
* ⚡ FastAPI REST API
* 🌐 Interactive web interface

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* FastAPI
* Pydantic
* Uvicorn

### Machine Learning & Data Processing

* Pandas
* Scikit-learn
* Joblib

### Deployment

* GitHub
* Render

---

## 📊 Input Features

The model uses the following information:

* Age
* Gender
* Country
* Academic Level
* Most Used Social Media Platform
* Primary Purpose of Social Media Use
* Average Daily Screen Time
* Daily Phone Unlocks
* Study Hours per Day
* Physical Activity Hours per Day
* Sleep Hours per Night
* Perceived Stress Level

---

## 🔄 How It Works

```text
User Input
    ↓
Frontend Form
    ↓
JavaScript Validation
    ↓
FastAPI /predict Endpoint
    ↓
Data Preprocessing
    ↓
Machine Learning Model
    ↓
Predicted Mental Health Score
    ↓
Interactive Result Display
```

---

## 🔌 API Endpoint

### `GET /`

Returns a basic welcome response from the FastAPI application.

### `POST /predict`

Accepts student information and returns the predicted mental health score.

Example response:

```json
{
  "predicted_mental_health_score": 6.78
}
```

---

## 📁 Project Structure

```text
mental-health-signal/
│
├── main.py
├── Mental_Health_Model.pkl
├── requirements.txt
│
├── index.html
├── style.css
└── script.js
```

---

## ▶️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/mental-health-signal.git
cd mental-health-signal
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Start the FastAPI server

```bash
uvicorn main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

FastAPI's interactive API documentation can be accessed at:

```text
http://127.0.0.1:8000/docs
```

---

## ☁️ Deployment

The backend can be deployed as a **Render Web Service**.

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
uvicorn main:app --host 0.0.0.0 --port $PORT
```

The frontend can be deployed as a **Render Static Site** using the same GitHub repository.

---

## 🎯 Project Goals

The main goals of this project are to:

* Apply machine learning to a real-world dataset.
* Understand the relationship between student lifestyle and digital habits.
* Build a complete ML-powered web application.
* Learn how to integrate a trained ML model with FastAPI.
* Create an interactive frontend for model predictions.
* Gain practical experience deploying an ML application.

---

## 📌 Important Note

The predicted score represents a **machine learning output based on the provided inputs**. It does not diagnose depression, anxiety, or any other mental health condition.

If you are experiencing mental health difficulties, consider speaking with a qualified mental health professional or someone you trust.

---

## 👩‍💻 Author

**Mehek Khan**

Computer Engineering Student
Interested in Machine Learning, Artificial Intelligence, Full-Stack Development, and Cybersecurity.

---

⭐ If you find this project interesting, feel free to explore the repository and connect with me.
