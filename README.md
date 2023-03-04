# Rainfall-Prediction
##Objectives
For this project we attempt to find the best KNN value to be used in the prediction of future rainfall of the area of our data

#THE DATA


It is gotten directly from kaggle. For this to happen the one needs to create a kaggle api link that downloads the dataset directly from the kaggle webpage and downloads it directly to the notebook.<br>
The library used is  opendatasets<br>
The data contains various weather indicators that are in our geological ecosystem.

#KNN


Knn  is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.<br>
By using KNN we can find an arcurate model to be used in prediction on the amount of rainfall to be found.<br>
This data need to standardizeed where we use the min max scaler for the data so as the model data is accurate and uniform for the prediction.

#RSEULTS


In this data we find that the best value of K=7 . This was selected since it has the lowest RMSE of all the K values of the model. This means that the most accurate number of k accurate neighbours for this model is 7 which we use in the prediction model for the rainfall data of the future.<br>
This model has an RMSE of  6.099903179579768 which is pretty accurate for this data. 
