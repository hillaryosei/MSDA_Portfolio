# D208 Predictive Modeling

## Course Summary
This course builds on initial data preparation, cleaning, and analysis, enabling students to make assertions vital to organizational needs. In this course, students conduct logistic regression and multiple regression to model the phenomena revealed by data. The course covers normality, homoscedasticity, and significance, preparing students to communicate findings and the limitations of those findings accurately to organizational leaders. This course has 2 practical assessments.

## Course Objectives
* **Logistic Regression:** The graduate employs logistic regression algorithms in describing phenomena.
* **Multiple Regression:** The graduate employs multiple regression algorithms with categorical and numerical predictors in describing phenomena.
* **Regression Implications:** The graduate makes assertions based on regression modeling.

## Practical Assessments Overview
### Task 1
This assignment requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and multiple linear regression to answer this question. Students create an initial multiple regression model, and generate a reduced multiple regression model by selecting variables based on a statistical justification and a model evaluation metric. Students also generate a number of univariate and bivariate visualizations of variables within the dataset.

My research question for this project was "Which factors contribute to the length of a hospital stay?" The analysis showed that the reduced model was statistically significant due to the high adjusted R<sup>2</sup> value of 0.998, meaning that the dependent variable can explain 99.8% of model explains 99.8% of the dependent variable "Initial_days" and that higher charges correlated with longer hospital stays. My report for this project can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D208/d208-task1.pdf) and the code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D208/d208-pa-task-1-revised.ipynb)

### Task 2
This assignment requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and logistic regression to answer this question. Students create an initial logistic regression model, and generate a reduced logistic regression model by selecting variables based on a statistical justification and a model evaluation metric. Students also generate univariate and bivariate visualizations of variables within the dataset.

My research question for this project was "Which factors contribute to patients being readmitted within one month of release?" In the [analysis](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D208/d208-task2.pdf), it was concluded that being initially admitted to the hospital through the ER and having medical conditions (e.g., stroke and high blood pressure) increased odds of being readmitted within one month. The code for this project can also be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D208/d208-task-2-pa-revised.ipynb)
