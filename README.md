# Introduction

The objective of this Kaggle competition is to complete one of two complementary COVID-19 forecasting competitions, by starting from a single state-level subcomponent via California, USA and seeing if we can forecast confirmed cases and fatalities. 

My objective is to take this dataset and produce accurate forecasts as a smaller scale of state-level. This serves as a practice in which I test multiple models to see which one produces the most accurate results and learn more about them.

Disclaimer from the Host: "We understand this is a serious situation, and in no way want to trivialize the human impact this crisis is causing by predicting fatalities. Our goal is to provide better methods for estimates that can assist medical and governmental institutions to prepare and adjust as pandemics unfold."

# Selection of Data

Data comes from John Hopkins CSSE [3].

It includes two files: ca_train.csv and ca_test.csv. The training file contains 62 days worth of COVID-19 population data (columns showed below).
Our dependent factors and are "confirmed cases" and "fatalities" in California between the dates of 1/22/2020 and 3/24/2020. 

# Methods

Tools:

- NumPy, Pandas, and Scikit-learn for data analysis and inference
- matplotlib for visualization
- GitHub for hosting/version control
- Jupyter Notebook as a programming environment

Inference methods used with Scikit:
- Linear regression
- Ridge Regression
- Logistic Regression

# Results

# Discussion

I found that the logistic model has a high percent accuracy rate for the training data, within the acceptable margin. This suggests that the logistic model can be a useful model for predicting covid spread within a region, which does make sense as infection spreads exponentially the more people are infected, and there usually comes a point where the population of infected will flatline.

This can help governments predict how many people will catch COVID within regions and accurately allocate resources to them. Since the COVID pandemic caught America so off guard, such prediction models can help the U.S government to know what to expect for future pandemics also.

When exploring other Kaggle notebooks, I found that with a bigger dataset, statistics tended to learn towards a logistic model instead. Wi

# Summary



[1] Kaggle Competition - https://www.kaggle.com/c/covid19-local-us-ca-forecasting-week-1/overview/description
[2] Scikit-Learn Algorithm Cheat Sheet - https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html
[3] John Hopkins CSSE - https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series
