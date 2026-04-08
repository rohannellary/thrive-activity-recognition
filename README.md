# 🏃 THRIVE: Human Activity Recognition using Wearable Sensors

An end-to-end machine learning pipeline for classifying human physical activities using wearable sensor (accelerometer) data.

---

## 🚀 Overview

This project focuses on detecting and classifying human activities such as walking, sitting, and running using time-series acceleration data collected from wearable devices.

The pipeline includes data preprocessing, feature engineering, model training, and evaluation to deliver robust activity classification.

---

## 🎯 Problem

Accurately classify physical activities from noisy, real-world sensor data to enable applications in health monitoring, fitness tracking, and human behavior analysis.

---

## 🧠 Approach

- Extracted statistical and temporal features from acceleration signals  
- Performed data cleaning, normalization, and preprocessing  
- Trained machine learning models (Random Forest / XGBoost)  
- Evaluated performance using **Macro F1-score** to handle class imbalance  

---

## 📊 Results

- Achieved **Macro F1-score > 0.91**  
- Consistent performance across multiple activity classes  
- Robust classification on unseen data  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 📁 Project Structure

```
src/
  train.py   # Model training, evaluation, and pipeline execution

README.md
requirements.txt
.gitignore
```

---

## ⚙️ How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Train and evaluate model
```bash
python src/train.py
```

---

## 🔥 Key Features

- End-to-end ML pipeline from raw sensor data to predictions  
- Feature engineering tailored for time-series signals  
- Robust evaluation using Macro F1-score  
- Modular and easy-to-extend code structure  

---
