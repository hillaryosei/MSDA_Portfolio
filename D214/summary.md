# D214 Graduate Data Analytics Capstone

## Course Summary
This course allows students to apply the academic and professional abilities developed as a graduate student. This capstone challenges students to integrate skills and knowledge from several program domains into one project. This course has three Practical Assessments.

## Course Objectives
* **Professional Readiness:** The graduate integrates and synthesizes competencies from across the degree program, thereby demonstrating the ability to participate in and contribute value to the chosen professional field.

## Practical Assessments Overview

### Task 1
This assignment requires students to develop a proposal for the topic of their capstone project, beginning with defining the intended research question as well as the null and alternative hypotheses for the study. Students must explain the context of the intended research and justify the processes, techniques, and tools to be used in the course of gathering, preparing, and analyzing the data. The capstone project is required to be "business-oriented" as a means to demonstrate preparation for entering the professional realm from the academic.

For my capstone project, I proposed using a dataset from [Kaggle](https://www.kaggle.com/datasets/colewelkins/cardiovascular-disease) that's consolidated from another [Kaggle dataset](https://www.kaggle.com/datasets/yasserh/heart-disease-dataset) and from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease) to determine whether demographic, lifestyle, and clinical factors can significantly impact the likelihood of cardiovascular disease using logistic regression analysis. The null hypothesis stated that none of the predictor variables are significantly associated with cardiovascular disease, while the alternative hypothesis stated that at least one of the predictor variables are significantly associated with the disease. The project used libraries such as Pandas, NumPy, Stastsmodels, Scikit-learn, Seaborn, and Matplotlib. The full proposal for my capstone project can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D214/task1/Hillary_Osei_Capstone_Topic_Approval_Form.pdf).

### Task 2
This assignment requires the student to perform their capstone research topic and create a report outlining the various steps of this process. This includes the research question, the data collection & preparation processes, the analysis addressing the research question, and a summary of the outcome of the analysis, including limitations, recommendations, and additional opportunities for supplemental research.

My research question for this project was "CDo demographic, lifestyle, and clinical factors significantly impact the likelihood of
cardiovascular disease?" After defining the null and alternative hypotheses using the evaluation metrics described in task 1, I collected and prepared the dataset, including removing irrelevant variables, detecting and handling missing and duplicate values, encoding categorical variables, and detecting and handling outliers. Exploratory data analysis was performed, giving a side-by-side of the univariate distributions and bivariate visualizations for each variable against the dependent variable. The model was then split 80/20 into training and testing sets, respectively, before creating the initial logistic regression model. Backward elimination was used to iteratively remove variables, using VIF first as a criteria then p-value. The VIF couldn't be more than 10 due to severe multicollinearity and p-values could be above 0.05 or else predictor variables would be considered statistically insiginificant. The reduced model revealed that factors such as BMI, cholesterol and glucose levels, gender, etc can impact likelihood of being diagnosed with the disease. The model has an accuracy score of 70%, indicating moderate predictive power.

My report for the project can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D214/task2/Hillary_Osei_D214_Task2_PA.pdf) and the code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D214/task2/d214-task2.ipynb).

### Task 3
This assignment requires the student to develop an executive summary of their capstone project from Task 2. This executive summary is intended for an audience with expertise in data analysis, and it must communicate the study problem & hypothesis, the data analysis process, study findings, study limitations, recommended actions (including avenues for further study), and expected corporate benefits. The executive summary for my capstone project can be viewed [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D214/task3/Hillary_Osei_D214_Task3_PA.pdf).

The student must also generate a multimedia presentation of their capstone project covering many of the same elements. This presentation is intended for a lay audience without prior knowledge or expertise in data analysis or the subject at issue. This video can be seen [here](https://wgu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=b147a014-385c-40b4-814f-b359003d2152).
