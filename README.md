# 🤖 PhishScan AI Model - Phishing Detection System

An AI-based phishing detection model that analyzes SMS/text messages and classifies them as **Spam (Phishing)** or **Ham (Legitimate)** using Machine Learning techniques.

---

## 📌 Overview

This project is part of the **FYP-PhishScan**, focusing on the **AI/ML backend**.  
It uses Natural Language Processing (NLP) and machine learning algorithms to detect phishing messages based on textual patterns.

---

## 🎯 Objectives

- Detect phishing and spam messages  
- Analyze text using NLP techniques  
- Train and evaluate ML models  
- Provide predictions via API for mobile/web apps  

---

## 🧠 Technologies Used

- **Python**
- **Pandas & NumPy** – Data handling  
- **Scikit-learn** – Preprocessing & evaluation  
- **XGBoost** – Classification model  
- **NLTK / Text Processing** – NLP techniques  
- **Jupyter Notebook** – Development & experimentation  

---

## ⚙️ Installation & Setup

### 📥 1. Clone the Repository


git clone https://github.com/irtazaahmad/FYP-PhishScan-AI-Model.git

### 📦 2. Install Dependencies

pip install -r requirements.txt

### ▶️ 3. Run the Notebook
 
jupyter notebook

### Open:

main.ipynb

### 🔍 How It Works
- Load SMS dataset
- Clean and preprocess text
- Convert text into numerical features (Vectorization)
- Train ML model (XGBoost)
- Predict whether message is:
- ✅ Ham (Safe)
- 🚨 Spam (Phishing)

