# Skin_Treatment-classification
A machine learning project that classifies appropriate skin treatments based on various features such as skin type, symptoms, and conditions. The model analyzes input data to recommend suitable treatment categories, aiding in quick and automated dermatological decision support.

Project Overview

This project analyzes clinical-style feature data (F1–F30) to classify or predict skin treatment outcomes. It demonstrates a complete ML pipeline from preprocessing to model evaluation.

📊 1008 patient records
🔢 32 numerical features
🧠 Model-driven treatment prediction

Key Characteristics
Contains minor missing values in some features
Wide feature variability (high standard deviation in several features)
Includes statistical distribution (mean, min, max, quartiles)

Models & Approach
🔹 Baseline Model
Logistic Regression
Simple, interpretable
Establishes initial benchmark performance
🔹 Final Model
Random Forest Regressor
Captures non-linear relationships
Handles feature interactions effectively
Provides improved predictive performance

Data Collection → Data Cleaning → EDA → Feature Processing → 
Model Training → Evaluation → Prediction

Results & Insights
Random Forest outperforms Logistic Regression in capturing complex patterns
Feature variability plays a significant role in prediction accuracy
Ensemble methods provide more stable results
