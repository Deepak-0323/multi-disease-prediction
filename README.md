# multi-disease-prediction
Multi-Disease Prediction System using Machine Learning, FastAPI, and Streamlit

# 🩺 Multi-Disease Prediction System

## 📌 Overview

This project is an end-to-end Machine Learning system that predicts the likelihood of three major diseases:

* Diabetes
* Heart Disease
* Kidney Disease

It uses trained ML models served via a FastAPI backend and an interactive Streamlit frontend for real-time predictions.

---

## 🚀 Features

* Predict multiple diseases from a single interface
* Separate ML models for each disease
* FastAPI backend for model inference
* Streamlit frontend for user interaction
* Real-time predictions
* Clean and user-friendly UI

---

## 🛠 Tech Stack

* Python
* Scikit-learn
* XGBoost
* FastAPI
* Streamlit
* Pandas & NumPy
* Joblib

---

## 📁 Project Structure

```
multi-disease-prediction/
│
├── backend/
│   └── main.py
│
├── frontend/
│   └── app.py
│
├── models/
│   ├── diabetes_model.pkl
│   ├── heart_model.pkl
│   └── kidney_model.pkl
│
├── data/
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/YOUR_USERNAME/multi-disease-prediction.git
cd multi-disease-prediction
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate   (Windows)
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Start Backend (FastAPI)

```
uvicorn backend.main:app --reload
```

API will run at:

```
http://127.0.0.1:8000
```

---

### Start Frontend (Streamlit)

Open a new terminal and run:

```
python -m streamlit run frontend/app.py
```

Frontend will run at:

```
http://localhost:8501
```

---

## 🧠 How It Works

1. User enters health parameters in the UI
2. Streamlit sends data to FastAPI
3. FastAPI processes input and calls ML model
4. Model returns prediction
5. Result is displayed on UI

---

## 📊 Models Used

* **Diabetes** → XGBoost Classifier
* **Heart Disease** → Random Forest Classifier
* **Kidney Disease** → Random Forest Classifier

---

## 📌 Example Predictions

* Diabetes → Diabetic / Non-Diabetic
* Heart Disease → Detected / Not Detected
* Kidney Disease → Disease / No Disease

---

## 📷 Screenshots (Optional)

*Add screenshots of your UI here*

---

## 🔮 Future Improvements

* Add prediction probability (confidence score)
* Improve UI with better design
* Deploy project online
* Add more diseases


## ⭐ If you like this project, give it a star!


Title:
Multi-Disease Prediction System using Machine Learning and FastAPI

Technologies Used:
Python, Scikit-learn, XGBoost, FastAPI, Streamlit, Pandas, NumPy

Short Description (for resume)

Developed an end-to-end machine learning system to predict Diabetes, Heart Disease, and Kidney Disease using multiple ML models. Built a FastAPI backend for model inference and a Streamlit frontend for interactive user input and prediction visualization.

uvicorn backend.main:app --reload ///backend
python -m streamlit run frontend/app.py  ///frontend 
---

## 👨‍💻 Author

Deepak Chawhan

---
