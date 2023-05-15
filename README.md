ML - Binary Classification
Overview
The aim of this project is to develop a machine learning model to predict whether salary of an individual is greater than or equal to 50,000 or not, based on a set of input features. The target variable is a Binary value, and the problem is therefore a classification problem.

Data
The dataset used in this project consists of 43957 instances with 11 features each. The data has been preprocessed and cleaned, and but there are missing values.
There are two datasets available 
	1. train.csv
	2. test.csv
I have also added output dataset - "Submissions_outcome.csv"

Methodology
The following steps were taken to develop and evaluate the classification model:

Data exploration and visualization
Feature engineering and selection
Model selection and tuning
Model evaluation and interpretation
The models that were tested include XGBClassifier, RandomForestClassifier. The performance metrics used to evaluate the models include Classification_report, confusion_matrix, precision_recall_f1score.

Results
The best performing model was XGBClassifier with an accuracy score of 0.86.

Conclusion
The developed model has shown promising results in classifying the target variable based on the input features. However, there is always room for improvement.

Dependencies
The project was implemented Python3 using the following dependencies:

scikit-learn
xgboost
pandas
