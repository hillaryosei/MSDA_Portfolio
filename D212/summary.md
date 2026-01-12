# D212 Data Mining II

## Course Summary
This course adds vital tools to the data analytics arsenal that incorporates unsupervised models. This course explains when, how, and why to use these tools to best meet organizational needs. This course has three Practical Assessments.

## Course Objectives
* **Hierarchical & K-Means Clustering Techniques:** The graduate applies clustering techniques to accurately predict outcomes of interest.
* **Principal Component Analysis:** The graduate implements dimension reduction methods to identify significant variables.
* **Market Basket Analysis:** The graduate predicts patterns in data using association rules and lift analysis.

## Practical Assessment Overviews

### Task 1
This assignment requires the student to use one either K-means or hierarchical clustering on one of the two provided datasets (medical or churn) to analyze the data. After selecting the variables of interest, the student generates a clustering model to facilitate this analysis. The student then communicates the results of their analysis and evaluates the model.

For this project, similar to the other assignemnts, was focused on identifying patient groups by features heavily correlated to the length of their hospital visits using K-means clustering. My report for this project can be viewed [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D212/task1/d212-task1.pdf) and the accompanying code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D212/task1/d212-task1-v3.ipynb).

## Task 2
This assignment requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and Principal Component Analysis (PCA) to reduce the dimensionality of the dataset (over 50 features). The student identifies the number of principal components and the variance of each component, before addressing the research question with those principal components.

My research question for this project was "What are the patterns in patient characteristics that can help hospitals better manage patient admissions?" The dataset included 11 continuous variables that would be incorporated into PCA. After conducting the PCA, Kaiser Criterion was used to determine the number of components to retain (being 5) and the cumulative variance was calculated, showing that 61.70% of the variance in the original dataset was explained by the 5 components. My report for the project can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D212/task2/d212-task2.pdf) and the code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D212/task2/d212-task-2-v3.ipynb).

## Task 3
This assignment requires the student to develop and answer a research question regarding one of two new datasets, using market basket analysis and association rules to analyze customer behaviors.

My research question for this project was "What other medications are commonly prescribed or purchased alongside Losartan?" From the market basket analysis, I found that prescriptions such as glyburide, carvedilol, diazepam, and amphetamine salt combo X are associated with Losartan more often than change due to its lift score above 1. My report for this project, can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D212/task3/d212-task3.pdf) and the code [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D212/task3/d212-task3.ipynb).
