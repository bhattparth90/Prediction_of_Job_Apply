# Prediction_of_Job_Apply_rate
Using Classification algorithms to predict whether a candidate will apply for the job or not

The problem of interest is the prediction of apply rate. Imagine a user visiting any job site, and
performing a job search. From the set of displayed results, user clicks on certain ones that she is
interested in, and after checking job descriptions, she further clicks on apply button therein to land in
to an application page. The apply rate is defined as the fraction of applies (after visiting job description
pages), and the goal is to predict this metric using the dataset described in the following section.

There are two files
1. In the ipython notebook , I have implemented Logistic Regression and random forest alogrithms to predict the application.
Since the data was highly imbalanced, I have used libraries like SMOTE to balance the classes.

2. The html file contains the same dataset but I have used XGBoost algorithm to predict the classes.
The algorithm is tuned properly and imbalance class is also handled appropriately.

The prediction by XGBoost works better than the other two algorithms in terms of accuracy,precision and AUC
