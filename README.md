# Heart Stroke Prediction System

A Machine Learning-based application that predicts the likelihood of heart stroke using patient health data. The project leverages a **K-Nearest Neighbors (KNN)** model along with preprocessing techniques to deliver accurate predictions.

---

## Overview

Heart stroke is one of the leading causes of death worldwide. Early prediction can help in timely medical intervention.

This project aims to:
- Analyze patient health data  
- Train a machine learning model  
- Provide real-time stroke risk prediction  

---

## Model Details

- **Algorithm Used:** K-Nearest Neighbors (KNN)  
- **Preprocessing:**
  - Feature scaling using `StandardScaler`
  - Handling structured medical data  
- **Model Persistence:** Saved using `joblib`

---

## Project Structure

```
heart-stroke-prediction/
│
├── app.py
├── heart.ipynb
├── heart.csv
│
├── models/
│   ├── heart_columns.pkl
│   ├── heart_scaler.pkl
│   └── knn_heart_model.pkl
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/anshiikkaaa/heart-stroke-prediction.git
cd heart-stroke-prediction
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Running the Application

```bash
python app.py
```

> If using Streamlit:
```bash
streamlit run app.py
```

---

## Dataset Description

The dataset contains medical attributes used to predict heart disease.

### Features:
- Age, Sex  
- ChestPainType  
- RestingBP  
- Cholesterol  
- FastingBS  
- RestingECG  
- MaxHR  
- ExerciseAngina  
- Oldpeak  
- ST_Slope  

---

## Features

- Machine Learning-based prediction  
- Pre-trained model for instant use  
- Clean and structured code  
- Easy to understand and extend  

---

## Future Improvements

- Add more ML models (Random Forest, Logistic Regression)  
- Improve accuracy with hyperparameter tuning  
- Deploy using Streamlit or Flask  
- Add better UI  