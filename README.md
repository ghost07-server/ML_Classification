<h1>ML - Binary Classification</h1>

<h3>Overview</h3>

<p>The aim of this project is to develop a machine learning model to predict whether salary of an individual is greater than or equal to 50,000 or not, based on a set of input features. The target variable is a Binary value, and the problem is therefore a classification problem.</p>

<h3>Data</h3>

The dataset used in this project consists of 43957 instances with 11 features each. The data has been preprocessed and cleaned, and but there are missing values.

There are two datasets available<br>
<ol>
	<li>train.csv</li>
	<li>test.csv</li>
</ol>
I have also added output dataset - "Submissions_outcome.csv"<br>

<h3>Methodology</h3>

The following steps were taken to develop and evaluate the classification model:

Data exploration and visualization

Feature engineering and selection

Model selection and tuning

<h3>Model evaluation and interpretation</h3>

The models that were tested include XGBClassifier, RandomForestClassifier. The performance metrics used to evaluate the models include Classification_report, confusion_matrix, precision_recall_f1score.

<h3>Results</h3>
The best performing model was XGBClassifier with an accuracy score of 0.86.

<h3>Conclusion</h3>
The developed model has shown promising results in classifying the target variable based on the input features. However, there is always room for improvement.

<h3>Dependencies</h3>
The project was implemented Python3 using the following dependencies:


scikit-learn

xgboost

pandas
