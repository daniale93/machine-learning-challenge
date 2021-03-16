# analysis

In order to analyze exoplanet data from NASA, we will be creating 2 different models that will classify candidates.


Model 1: Linear SVC

1. First of all we select features that will be used as 'x' in our model. In this case we want all available features to be included.

2. We split the data into training and testing, and train using SVC algorithm.

3. Training Data Score: 0.8445546442876216
  Testing Data Score: 0.8506864988558352

Model 2: Logistic Regression

1. Similarly, we select all features to perform our logistic regression model. 

2.  We split the data into training and testing, and train using logistic regression. 

3. Training Data Score: 0.8552355521647912
Testing Data Score: 0.8586956521739131



Comparing results from both models, we can see a small improvement in our model using logistic regression compared to linear SVC. 