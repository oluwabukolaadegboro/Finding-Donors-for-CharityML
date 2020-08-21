# Finding-Donors-for-CharityML

This constitutes part of my Udacity Machine Learning Nanodegree program. In this project, I applied my knowledge of supervised learning techniques to identify the top potential donors for a charity organization company, CharityML. The goal of the project is to build a model which accurately predicts individuals with income greater than $50,000. This is used to identify potential donors for the organization and hence minimize donation letters to be sent.

The dataset contains approximately 32,000 data points, with each datapoint having 13 features.

I investigated different learning algorithms to determine which is best at modelling the data. They include the Naive Predictor, and Ensemble Methods. I also investigated the F-beta score and Accuracy score metrics to properly evaluate the performance of each model. In the end, I chose a tree-based model because I could rank the importance of each feature when making predictions. With fewer features required to train, there was a significant decrease in training and prediction time with very little decrease in the performance metrics.

At the end of the project, I was able to optimize the best model that provides the highest donation yield while also reducing the total number of letters being sent.
