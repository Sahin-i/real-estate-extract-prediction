# Real Estate ML Model

This project predicts whether a property has a legal extract ("çıxarış").

## Features
- Location (lat, lng)
- Area
- Category
- Repair status

## Model
- RandomForestClassifier

## Results
ROC-AUC:  0.9688
F1 Score: 0.9631
              precision    recall  f1-score   support

           0       0.90      0.81      0.85      4242
           1       0.95      0.98      0.96     15913

    accuracy                           0.94     20155
   macro avg       0.92      0.89      0.91     20155
weighted avg       0.94      0.94      0.94     20155
