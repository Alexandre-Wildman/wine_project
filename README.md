# wine_project
A tutorial about using machine learning to predict the wine traits that cause the most impact on wine quality.
What is the problem statement?




What is the problem statement?

You have been hired as a junior food scientist / engineer to help increase the quality of the wine at a large winery. You know that there are certain compounds in wien that make it taste great. A few of these include the fixed acidity and the volatile acidity, residual sugar ( i dislike a sweet wine but some people do! ) , sulphates , % alcohol and so on.
Your manager gives you some data collected from a team of food scientists that just spent hundreds of hours collecting you some good data. Your then going to take this data and create a machine learning algortithim that is going help you predict the quality of the wine and therefore find which key parameters that will help you improve the wine at this winery!

Two datasets were created, using red and white wine samples. The inputs include objective tests (e.g. PH values) and the output is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent). Several data mining methods were applied to model these datasets under a regression approach. The support vector machine model achieved the best results. Several metrics were computed: MAD, confusion matrix for a fixed error tolerance (T), etc. Also, we plot the relative importances of the input variables (as measured by a sensitivity analysis procedure). P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

1) Understand what kind of problem you have from a machine learning perspective. 2) This tutorial will focus on supervised learning.

Supervised Learning Models are fit on training data comprised of inputs and outputs and used to make predictions on test sets where only the inputs are provided and the outputs from the model are compared to the withheld target variables and used to estimate the skill of the model. In a few words: you are given training data and you are asked to predict some output data. This can be further broken down into

Classification: Supervised learning problem that involves predicting a class label. Regression: Supervised learning problem that involves predicting a numerical label.

Steps to do

1) Understand what the data looks like and what it could mean.
2) Pre process the data so you can load into into python and make it useabel & readable to your algorithim.

3) Need to take a section of your data and split into Testing data and Training datasets.

training set—a subset to train a model. test set—a subset to test the trained model. Make sure that your test set meets the following two conditions:

Is large enough to yield statistically meaningful results. Is representative of the data set as a whole. In other words, don't pick a test set with different characteristics than the training set. Key thing. Never train on test data. If you are seeing surprisingly good results on your evaluation metrics, it might be a sign that you are accidentally training on the test set.

4) Choose a model that works well with your data and what you want to achieve. In this case we will be using a random forest model.

5) Train the random forest model.

6) Evaluate on your test data

7) You now havea trained random forest model

8) GIve your algorithim some new data , the test data, and see what it predicts!
