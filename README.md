# THRIVE: Human Activity Recognition using Wearable Sensors

## Overview
End-to-end machine learning pipeline for classifying human activities using wearable sensor (accelerometer) data.

## Problem
Accurately classify physical activities (e.g., walking, sitting, running) from sensor data.

## Approach
- Feature extraction from acceleration signals
- Model: Random Forest / XGBoost (update with what you used)
- Data preprocessing and normalization
- Evaluation using Macro F1-score

## Results
- Achieved Macro F1-score > 0.91
- Robust classification across multiple activity types

## Tech Stack
Python · Pandas · Scikit-learn · NumPy

## How to Run
```bash
pip install -r requirements.txt
python src/train.py

