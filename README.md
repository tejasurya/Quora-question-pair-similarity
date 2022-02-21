# Quora-question-pair-similarity

 Problem Statement
- Identify which questions asked on Quora are duplicates of questions that have already been asked. 
- This could be useful to instantly provide answers to questions that have already been answered. 
- We are tasked with predicting whether a pair of questions are duplicates or not. 

<h3> Data Overview </h3>
<p> 
- Data will be in a file Train.csv <br>
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate <br>
- Size of Train.csv - 60MB <br>
- Number of rows in Train.csv = 404,290
</p>
<h3>  Type of Machine Leaning Problem </h3>
<p> It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not. </p>
<h3> Performance Metric </h3>

* log-loss 
* Binary Confusion Matrix

<h4> Exploratory Data Analysis </h4>
<h4>Basic Feature Extraction</h4>

<h2> ML models applied <h2>
- Binary classification done using Logistic Regression, Linear SVM with hyperparameter tuning and XGBoost model. 

  
