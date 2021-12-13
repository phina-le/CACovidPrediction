# Introduction

The objective of this project is to complete one of two complementary COVID-19 forecasting competitions posted on Kaggle[1], by starting from a single state-level subcomponent via California, USA and seeing if we can forecast confirmed cases and fatalities. The White House Office of Science and Technology Policy has pulled together a coalition of research groups and companies to address key open scientific questions on COVID-19:

1. What do we know about non-pharmaceutical interventions? 
2. What is known about transmission, incubation, and environmental stability? 
3. What do we know about COVID-19 risk factors? 
4. What has been published about medical care?

My objective is to take this dataset and produce accurate forecasts and possibly identify factors that appear to impact the transmission rate of COVID-19, while answering the above questions. This serves as a practice in which I test multiple models to see which one produces the most accurate results using the scikit-learn algorithm cheat sheet ("few features should be important" bubble yes AND no)[2]

# Selection of Data

Data comes from John Hopkins CSSE [3], uninvolved from the Kaggle competition.

It includes two files: ca_train.csv and ca_test.csv. The training file contains 62 days worth of infromation on the confirmed COVID-19 cases and fatalities in California between the dates of 1/22/2020 and 3/24/2020. 

# Methods

Tools:

- NumPy, SciPy, Pandas, and Scikit-learn for data analysis and inference
- GitHub for hosting/version control
- Jupyter Notebook as a programming environment

Inference methods used with Scikit:

Linear regression model - SGD Regressor

# Results



[1] Kaggle Competition - https://www.kaggle.com/c/covid19-local-us-ca-forecasting-week-1/overview/description
[2] Scikit-Learn Algorithm Cheat Sheet - https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html
[3] John Hopkins CSSE - https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series
