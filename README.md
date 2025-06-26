# Career-prediction-using-ML

This project is a smart Career Prediction System that uses personality traits, aptitude scores, and machine learning techniques to suggest the most suitable career path for a user. It is built using Python, scikit-learn, and Random Forest Classification, and includes advanced handling for class imbalance, feature importance analysis, and explainable predictions.

🧠 What It Does

The model analyzes user inputs such as Big Five personality traits (OCEAN) and various aptitude scores (Numerical, Verbal, Spatial, etc.) to predict the most suitable career using a trained machine learning model. It also provides a reason for the prediction by identifying the top contributing features.

🚀 Key Features:

✅ Handles Missing Data using appropriate imputers for numerical and categorical features

🔁 Label Encoding for categorical variables

📉 Class Balancing using oversampling with resample() to handle rare career categories

🔍 Hyperparameter Tuning using GridSearchCV for optimized model performance

🌲 Random Forest Classifier for robust multi-class classification

💡 Feature Importance Visualization for transparency and explainability

📊 Top-5 Feature Reasoning for every prediction

📈 Accuracy Reporting on test data

🔮 Single User Prediction with full reasoning breakdown

📂 Input Features:

The model uses the following 10 input features:

O_score – Openness

C_score – Conscientiousness

E_score – Extraversion

A_score – Agreeableness

N_score – Neuroticism

Numerical Aptitude

Spatial Aptitude

Perceptual Aptitude

Abstract Reasoning

Verbal Reasoning

These features can be collected from psychometric assessments.
 
