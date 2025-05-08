# Network Intrusion Detection System

## Overview
This project implements a Machine Learning-based Network Intrusion Detection System (NIDS) using Random Forest and XGBoost classifiers to detect malicious network activity.

## Requirements
Ensure you have the following dependencies installed before running the project:
```
pip install pandas numpy scikit-learn xgboost matplotlib
```

## Running the Code
1. Place the dataset (`Data.csv`) in the project directory.
2. Open the Jupyter Notebook (`NetworkIntrusionDetection.ipynb`).
3. Run all cells to preprocess data, train models, and evaluate results.
4. The evaluation metrics (accuracy, precision, recall, F1-score) will be displayed.

## Results
- The trained models classify network traffic as normal or malicious.
- Performance metrics such as accuracy, precision, recall, and confusion matrix are generated.

## Future Enhancements
- Improve model accuracy through hyperparameter tuning.
- Implement deep learning techniques for better detection.
- Deploy the model for real-time intrusion monitoring.
