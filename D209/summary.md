# D209 Data Mining

## Course Summary
This course expands predictive modeling into nonlinear dimensions, enhancing the capabilities and effectiveness of the data analytics lifecycle. In this course, learners implement supervised models (classification and prediction data mining models) to unearth relationships among variables that are not apparent with more surface-level techniques. The course provides frameworks for assessing models’ sensitivity and specificity. This course has two Practical Assessments.

## Course Objectives
*  **Classification Data Mining Models:** The graduate applies observations to appropriate classes and categories using classification models.
*  **Predictive Data Mining Models:** The graduate implements prediction data mining models to find hard-to-spot relationships among variables.
*  **Data Mining Model Performance:** The graduate evaluates data mining model performance for precision, accuracy, and model comparison.

### Task 1
This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and k-nearest neighbor (KNN) or Naive Bayes classification analysis. Students identify a set of variables to use and split the data into training and test sets before performing their classification analysis to answer this research question.

My research question for this project was "What are the major predictor variables that can predict or determine patient readmissions?" I generated a KNN model with an accuracy score of 0.62 and an AUC score of 0.49, indicating that the model cannot effectively identify predictor variables that can determine patient readmissions. My report for this project can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D209/d209-task1.pdf) and the code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D209/d209-task-1-revised.ipynb).

### Task 2
This project requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and decision trees, random forests, or advanced regression (lasso or ridge) analysis. Students identify a set of variables to use and split the data into training and test sets before performing their classification analysis to answer this research question.

My research question for this project was "What are the major predictor variables that can predict or determine patient readmissions?". I reused this question in hopes of getting a more accurate, effective model. I generated a decision tree model that used Grid Search to find the most optimal hyperparameters to identify variables that have the most influence in patient readmissions. The decision tree model had a test accuracy of 0.65 and an AUC score of 0.50, with the accuracy score being a slight improvement versus the KNN model from task 1. My report for this project can be viewed [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D209/d209-task2.pdf) and my code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D209/d209-task-2-pa.ipynb).

