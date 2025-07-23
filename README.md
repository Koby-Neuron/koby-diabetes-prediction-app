# Diabetes Prediction Web App

A simple and practical machine learning web app to predict whether a patient is likely to have diabetes based on health data inputs.

## 📊 Project Overview

This project is based on the Pima Indians Diabetes dataset and demonstrates the complete machine learning pipeline:
- Data preprocessing & cleaning
- Feature engineering
- Model training using Logistic Regression
- Building a web interface with Streamlit

The app predicts diabetes likelihood using metrics like glucose, BMI, blood pressure, and more.

## 📁 Files Included

- `app.py`: Streamlit app code.
- `diabetes_prediction.ipynb`: Full Jupyter Notebook for preprocessing and model training.
- `model.pkl`: Trained Logistic Regression model saved with pickle.

## 🚀 Running the App

To run this app locally:

bash
# Clone the repo
git clone https://github.com/your-username/diabetes-prediction-web-app.git

# Install required packages
pip install -r requirements.txt

# Run the app
streamlit run app.py


## 📈 Model Performance

* Accuracy: 75%
* Classifier: Logistic regression
* F1-score: 0.77 (non-diabetic), 0.64 (diabetic)

This means the model performs fairly well in predicting both classes, with room for future tuning.

## 👨‍💻 About Me

This project was created by **Okobi Joseph Taiwo** as part of an application for a remote AI/ML internship at **Kinnovia**. I'm passionate about using data and machine learning to solve real-world problems and continually learning new tools and techniques in the field.

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy, Scikit-learn, Logistic Regression, XGBoost
* Streamlit
* Jupyter Notebook

