# 🎙️ Speech Emotion Recognition using KNN 🔬

**Full-Stack Speech Emotion Detection using Machine Learning and React**

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![React](https://img.shields.io/badge/frontend-React-blue.svg)
![Status](https://img.shields.io/badge/status-Completed-brightgreen.svg)

---

## 🧠 Project Overview

This project implements Speech Emotion Recognition (SER) by classifying human speech into emotional categories such as **Happy**, **Sad**, **Angry**, and **Neutral** using the **K-Nearest Neighbors (KNN)** algorithm.

The system extracts relevant features from audio signals using **Mel Frequency Cepstral Coefficients (MFCCs)** and applies supervised machine learning for emotion classification. The project also includes a **React-based frontend** for an interactive user interface and a **Python backend** to handle model predictions.

---

## ⚙️ Technologies Used

### Backend

* Python
* Librosa (Audio processing)
* NumPy
* Scikit-learn (Machine Learning)
* Flask (or your backend framework)

### Frontend

* React
* HTML & CSS
* JavaScript

---

## 📦 Key Components

* Audio pre-processing and feature extraction
* Emotion classification with K-Nearest Neighbors
* REST API for handling predictions
* React frontend for uploading audio files and displaying results
* Model evaluation with Confusion Matrix and Accuracy Score

---

## 📁 Project Structure

```
├── backend/                       
│   ├── data/                      
│   ├── venv/                      
│   ├── emotion_classification_model.pkl   
│   ├── main.py                    
│   ├── test.py                    
│   └── train.py                   
│  
├── frontend/                      
│   ├── public/                    
│   ├── src/                       
│   │   ├── components/            
│   │   ├── App.css  
│   │   ├── App.js  
│   │   ├── App.test.js  
│   │   ├── index.css  
│   │   ├── index.js  
│   │   ├── logo.svg  
│   │   ├── reportWebVitals.js  
│   │   └── setupTests.js  
│   ├── .gitignore  
│   ├── README.md                  
│   ├── package.json               
│   └── package-lock.json  
│  
├── uploads/                       
└── README.md                      
```

---

## 🖼️ Screenshots

| Upload Audio          | Emotion Prediction    |
| --![Output](https://github.com/user-attachments/assets/8236bda2-1db6-4164-9a97-dc230c4ebce4)
![WhatsApp Image 2025-06-22 at 14 31 23_9d2d3f71](https://github.com/user-attachments/assets/143b647a-f32f-4041-ab3b-a3fe7830d8d1)

| --------------- | --------------------- |
---

## 🔍 Features

✅ Speech emotion detection from audio input
✅ Interactive web interface to upload audio files
✅ Real-time emotion classification
✅ Model built using supervised learning (KNN)
✅ Clear project structure separating frontend and backend

---

## 🚀 Future Enhancements

* Support for additional emotion categories
* Real-time microphone input support
* Improved model performance with advanced classifiers
* Enhanced UI for better user experience

---

## 🛠️ Setup & Installation

### Backend

1. Navigate to `backend/`
2. Create virtual environment and activate:

   ```
   python -m venv venv  
   venv\Scripts\activate  # Windows  
   source venv/bin/activate  # macOS/Linux  
   ```
3. Install dependencies:

   ```
   pip install -r requirements.txt  
   ```
4. Run the backend:

   ```
   python main.py  
   ```

### Frontend

1. Navigate to `frontend/`
2. Install dependencies:

   ```
   npm install  
   ```
3. Run the frontend:

   ```
   npm start  
   ```

---

## 📬 Contact

For suggestions or queries:
**Sai Sruthi Karnatakapu** | [LinkedIn](https://www.linkedin.com/in/saisruthi-karnatakapu)
**Speech Emotion Detection | Full-Stack | KNN-based Machine Learning | React Frontend | Python Backend**

