# Netflix-Customer-Churn-Prediction-using-Machine-Learning-Pipeline
This project predicts whether a Netflix customer will churn or not. The model is built using a Scikit-Learn pipeline that handles preprocessing, encoding, feature selection, and model training. A Decision Tree classifier is used for prediction, and the trained pipeline is saved using pickle for future inference

## Project Workflow
1. Data Loading and Exploration
2. Data Preprocessing
3. Encoding Categorical Features

   * Ordinal Encoding for subscription type
   * One-Hot Encoding for other categorical features
4. Feature Selection using SelectKBest
5. Model Training using Decision Tree Classifier
6. Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
7. Cross Validation
8. Model Serialization using Pickle
9. Prediction using Saved Pipeline

## Model Performance
Accuracy: **98.7%**

Confusion Matrix:

[[492   6]
[ 6   496]]

Cross Validation Accuracy: **98.34%**

## Project Structure
Netflix_Pipelining.ipynb
Notebook containing data preprocessing, pipeline creation, model training, and evaluation

Prediction.ipynb
Notebook used to load the saved pipeline and make predictions on new input data

netflix_customer_churn.csv
Dataset used for training the model

pipe.pkl
Serialized trained pipeline saved using pickle

README.md
Project documentation

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-Learn
* Jupyter Notebook

## Learning Outcomes
* Implemented a complete machine learning pipeline
* Applied encoding techniques for categorical data
* Used feature selection methods
* Evaluated models using multiple metrics
* Performed cross validation
* Saved and reused trained models using pickle







