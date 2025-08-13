Machine Learning - Titanic Survival Prediction
Project Overview
The objective of this project was to develop a predictive machine learning model using the historic Titanic dataset. The model's purpose is to predict whether a passenger survived or not, based on a variety of features such as age, sex, passenger class, and family size.

This project follows a standard machine learning lifecycle, from data cleaning and exploratory data analysis to model training, evaluation, and deployment.

Features
The following key features were used in the analysis and model training:

Age: The age of the passenger.

Sex: The gender of the passenger.

Pclass: The passenger class (1st, 2nd, or 3rd).

Parch: The number of parents/children aboard.

SibSp: The number of siblings/spouses aboard.

Fare: The passenger fare.

Embarked: The port where the passenger embarked.

Methodology
The project workflow included the following steps:

Data Collection and Preparation: The Titanic dataset was loaded from a CSV file. Initial data cleaning involved handling missing values in columns like Age, Cabin, and Embarked, and dropping irrelevant columns like Name and PassengerId.

Exploratory Data Analysis (EDA): The relationships between different features and the survival outcome were analyzed to inform feature engineering and model selection.

Model Selection & Training: Several machine learning classifiers were considered and trained on the preprocessed data.

Model Evaluation: The performance of the trained models was evaluated using metrics such as accuracy, precision, recall, and F1-score.

Results
After evaluating several models, the Logistic Regression model was selected for its high accuracy and overall strong performance. The classification report for the final model is as follows:

Class

Precision

Recall

F1-Score

Support

Not Survived

0.97

0.95

0.96

266

Survived

0.91

0.95

0.93

152

Accuracy





0.95

418

Macro Avg

0.94

0.95

0.94

418

Weighted Avg

0.95

0.95

0.95

418

This shows the model is highly effective at predicting survival outcomes with an accuracy of 95%.

Technologies Used
Python

Pandas

Scikit-learn

Jupyter Notebook

How to Run
Clone this repository to your local machine.

Ensure you have the required libraries installed (pandas, scikit-learn, jupyter).

Open the New_titanic.ipynb notebook and run the cells.
