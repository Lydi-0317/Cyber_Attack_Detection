# Cyber Attack Detection using Machine Learning

This project focuses on detecting and classifying Cyber Attacks based on Network Traffic data. Machine Learning algorithms are used to identify malicious activities like DoS, Probe, R2L, and U2R attacks.

## Key Features

- Data Preprocessing & Feature Engineering
- Machine Learning Model Training using XGBoost
- Classification of attack types
- Real-World prediction simulation

## Files


- `Cyber_Attack_Detection.ipynb` - Main Jupyter Notebook
- `Unseen_real_world_data.csv` - Data for real-world testing
- `cyber_instrusion_model.joblib` - Trained model
- `*.joblib` - Encoders for categorical features

## Accuracy

Achieved over **86.21%** accuracy on test data.

## Getting Started

```bash

pip install -r requirements.txt

python predict_attack.py
