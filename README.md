# TikTok Claim Classification using Machine Learning

## Overview
This project implements a machine learning pipeline to classify TikTok video transcripts as either claims or opinions. The workflow includes data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation using ensemble learning techniques.

## Features
- Data preprocessing and cleaning
- Feature engineering using text-derived attributes
- Model training using Random Forest and XGBoost
- Hyperparameter tuning with GridSearchCV
- Evaluation using precision, recall, F1-score, and confusion matrix analysis

## Technologies Used
- Python
- Pandas
- NumPy
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Project Workflow
1. Data preprocessing and exploratory analysis
2. Train/validation/test splitting
3. Model training and tuning
4. Evaluation and comparison of models
5. Feature importance analysis

## Results
The project compared Random Forest and XGBoost classifiers for binary content classification and analyzed performance using standard ML evaluation metrics.

## Model Evaluation
### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)
## Repository Structure
- `notebook/` → Jupyter notebook implementation
- `images/` → visualizations and model outputs
- `requirements.txt` → project dependencies

## Future Improvements
- Add NLP embeddings
- Experiment with transformer-based architectures
- Deploy as a lightweight API service