# Medical Appointment No-Show Prediction

A machine learning project that analyzes medical appointment data to identify patterns behind missed appointments and predict patient no-shows.

## Objectives
- Analyze factors associated with missed appointments.
- Explore patient demographics, scheduling patterns, and medical conditions.
- Train and evaluate classification models.
- Compare model performance and identify an effective approach to no-show detection.

## Dataset
The project uses the Medical Appointment No Shows dataset (`KaggleV2-May-2016.csv`).

## Workflow
- Data inspection and cleaning
- Exploratory data analysis and visualization
- Feature engineering and preprocessing
- Model training and evaluation
- Random Forest hyperparameter tuning
- Prediction analysis and model export

## Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Best Model
The tuned Random Forest achieved **71.3% recall** for the no-show class and a **0.737 ROC-AUC** on the test set.

The model prioritizes identifying more potential no-shows, with a trade-off in precision and overall accuracy.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, and Joblib.

## Project Goal
Demonstrate an end-to-end machine learning workflow for understanding and predicting missed medical appointments.

