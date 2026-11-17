
# 🩺 Diabetes Risk Score Prediction Using Machine Learning

## 📌 Project Overview

It is a Machine Learning-based predictive analytics system that estimates a numerical diabetes risk score using patient health and lifestyle information.

The system uses a Regression approach to predict the target variable `diabetes_risk_score` based on 28 input features, including age, BMI, glucose levels, blood pressure, cholesterol, physical activity, diet, sleep, and other lifestyle factors.

Multiple regression algorithms are evaluated, and Polynomial Regression is selected as the final model based on the model evaluation results.

The trained model is integrated into an interactive Streamlit web interface to generate predictions from user-provided inputs.

## 🎯 Objectives

- Predict numerical diabetes risk scores using Machine Learning.
- Analyze patient health and lifestyle features.
- Implement and compare multiple regression algorithms.
- Perform feature selection and hyperparameter tuning.
- Deploy the trained model using Streamlit.
- Provide an interactive and user-friendly prediction interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Scikit-learn | Machine Learning |
| Joblib | Model Serialization |
| Streamlit | Web Interface |
| Matplotlib / Seaborn | Data Visualization |
| Jupyter Notebook | Model Development |

## 📊 Input Features

The system uses 28 patient health and lifestyle features.

**Health-related features**
- Age
- BMI
- Waist-to-Hip Ratio
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Total Cholesterol
- LDL Cholesterol
- HDL Cholesterol
- Triglycerides
- Fasting Glucose
- Postprandial Glucose
- HbA1c
- Insulin Level
- Heart Rate
- Family History of Diabetes
- Cardiovascular History
- Hypertension History

**Lifestyle and demographic features**
- Gender
- Ethnicity
- Income Level
- Education Level
- Employment Status
- Smoking Status
- Alcohol Consumption per Week
- Physical Activity Minutes per Week
- Sleep Hours per Day
- Diet Score
- Screen Time Hours per Day

## 🤖 Machine Learning Algorithms

The following regression algorithms are evaluated:

1. K-Nearest Neighbors (KNN) Regressor
2. Decision Tree Regressor
3. Linear Regression
4. Polynomial Regression

Model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

**Final Selected Model:** Polynomial Regression

## ⚙️ Project Workflow

1. Dataset loading and inspection.
2. Data preprocessing.
3. Feature selection.
4. Train-test splitting.
5. Model training.
6. Hyperparameter tuning.
7. Model comparison and evaluation.
8. Saving the best trained model using Joblib.
9. Streamlit application development.
10. Generating predictions using patient inputs.

## 📁 Project Structure

```text
Diabetes Prediction/
│
├── diab_app.py
├── bestest_diabetes_model.pkl
├── diabetes_prediction.ipynb
├── README.md
│
└── requirements.txt
```

## 🚀 Installation and Execution

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Navigate to the project folder**

```bash
cd Diabetes Risk Score Prediction Using Machine Learning
```

**Step 3: Install dependencies**

```bash
pip install -r requirements.txt
```

**Step 4: Run the Streamlit application**

```bash
python -m streamlit run diab_app.py
```

**Step 5:** Open the local URL displayed in the terminal to access the application.

## 📈 Application Features

- Interactive patient input form.
- 28 health and lifestyle input features.
- Machine Learning-based numerical prediction.
- Polynomial Regression model integration.
- Prediction result visualization.
- Patient input summary.
- Downloadable prediction details in CSV format.
- User-friendly Streamlit interface.

## ⚠️ Disclaimer

This project is developed for educational and research purposes using a synthetic dataset. The predicted score is an experimental model output and is not a clinically validated diabetes risk assessment or medical diagnosis. It should not be used for medical decision-making.

## 👩‍💻 Developed Using

Python | Scikit-learn | Pandas | NumPy | Joblib | Streamlit

**Project:** Diabetes Risk Score Prediction Using Machine Learning
