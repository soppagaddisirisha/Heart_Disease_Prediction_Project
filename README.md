# Heart_Disease_Prediction_Project
A machine learning project that predicts whether a person is at risk of heart disease based on clinical and lifestyle attributes. This project demonstrates an end-to-end workflow including data cleaning, EDA, feature engineering, model training, evaluation, and real-time prediction.

PROJECT OVERVIEW:
Heart disease is one of the leading causes of mortality worldwide. Early prediction can help in timely diagnosis and prevention.This project uses Logistic Regression to classify whether a patient is likely to have heart disease based on medical parameters such as cholesterol level, blood pressure, chest pain type, etc.

DATASET:
1.Uses the Heart Disease Dataset from UCI Machine Learning Repository.
2.Contains features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, maximum heart rate, exercise-induced angina, and more.

TECH STACK:
1.Python
2.Pandas, NumPy
3.Scikit-learn
4.Matplotlib/Seaborn
5.Joblib

MODEL USED:
Chose Logistic Regression because:
It is interpretable
Works well for binary classification
Fast and efficient
Suitable for healthcare datasets

INSTALLATION:
git clone https://github.com/soppagaddisirisha/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt

USAGE:
1.Run the Jupyter notebook to explore data and train the model:
jupyter notebook HeartDiseasePrediction.ipynb
2.Input patient details in the interface to get a prediction.

MODEL PERFORMANCE:
1.Accuracy, precision, recall, and F1-score are calculated for evaluating model performance.
2.Visualizations of feature importance and model predictions included.
