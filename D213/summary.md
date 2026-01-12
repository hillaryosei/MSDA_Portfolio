# D213 Advanced Data Analytics

## Course Summary
This course preps students for career-long growth in steadily advancing tools and techniques and provides emerging concepts in data analysis. 
This course hones the mental and theoretical flexibility that will be required of analysts in the coming decades while grounding their approach firmly in ethical 
and organizational-need-focused practice. Topics include machine learning, neural networks, randomness, and unconventional data sources. This course has two Practical Assessments.

## Course Objectives
* **Time Series Analysis:** The graduate applies time series models in generating forecasts.
* **Neural Networks:** The graduate builds neural networks in the context of machine-learning modeling.
* **Natural Language Processing:** The graduate extracts insights from text data using effective and appropriate natural processing (NLP) models.

## Practical Assessments Overview
### Task 1
This assignment requires the student to develop and answer a research question, using one of the two provided datasets (medical or churn) and ARIMA time series modeling techniques. 
The student must generate a number of time series visualizations, evaluate the stationarity of the series, account for trends and seasonality, and develop a forecast in the course of addressing 
this research question.

My research question for this project was "Can we forescast daily revenue in the medical industry over the remainder of the year using a time-series model?" 
Using 20 months of daily revenue data, I generated a forecast of the next 4 months of daily revenues to compare to the observed values. 
My report for this project can be viewed [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D213/task1/Hillary_Osei_D213_Task1_PA%20(V2).pdf) and the code can be viewed 
[here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D213/task1/d213-task1.ipynb).

## Task 2
This assignment requires the student to select one of a number of authorized datasets to develop a research question to be addressed through sentiment analysis, 
using Natural Language Processing (NLP) and machine learning within a neural network. 
The student must perform an exploratory data analysis of their selected dataset, tokenize the data, and develop a model using TensorFlow, 
including justification of both hyperparameters of that model and the neural network layers involved. Finally, the effectiveness of the generated model must be evaluated.

I chose to use an IMDB review dataset for this project. I used a recurrent neural network (RNN) to perform a sentiment analysis on user reviews of movies to 
predict whether it would automatically be classified as positive or negative using NLP techniques. Unusual characters, stopwords, etc had to be removed and after the data was tokenized (using Keras Tokenizer), 
sets for training, validation, and testing 
were generated and padded. A TensorFlow model was generated with 94,000+ parameters, using an Embedding layer followed by a GRU layer, and then 3
Dense nodes. Early Stopping was used as the sstopping criteria to prevent overfitting for the model and a patience of 2 was set.
The model had a training accuracy of 52.1% and a testing accuracy of 49.3%, meaning that the model does not effectively determine a movie viewer's sentiments.
My report for this project can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D213/task2/Hillary_Osei_D213_Task2_PA%20(V2).pdf) and my code can be found [here](https://github.com/hillaryosei/MSDA_Portfolio/blob/main/D213/task2/d213-task-2-v2.ipynb).
