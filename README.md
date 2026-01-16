# Seoul Bike Sharing Demand Prediction

## Project Overview (What & Why)
This project predicts hourly bike-sharing demand in Seoul using historical usage, weather, and time-related data.  
The objective is to demonstrate an end-to-end data science workflow, from data cleaning to model evaluation, using a real-world dataset.

---

## End-to-End Pipeline
- Data understanding and exploratory analysis  
- Data cleaning (missing values, duplicates, outliers with domain logic)  
- Feature engineering (time-based features, transformations, encoding)  
- Model training and comparison  
- Hyperparameter tuning  
- Model evaluation using multiple metrics  

---

## Models Used
- Decision Tree Regression (baseline, interpretable)
- Random Forest Regression (ensemble-based)
- AdaBoost Regression (boosting approach)
- Neural Network (Multi-Layer Perceptron)

---

## Evaluation Summary
Models are evaluated using:
- R²
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Relative Error (MARE)
- Signal-to-Noise Ratio (SNR)

The neural network achieved the strongest overall predictive performance, while Random Forest provided a strong balance between accuracy and stability.

---

## What This Repository Demonstrates
- Practical data cleaning and preprocessing
- Feature engineering based on real-world logic
- Training and comparing multiple machine learning models
- Hyperparameter tuning and generalisation awareness
- Clear analytical reasoning and structured workflow
