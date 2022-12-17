# Wine-Fraud-Classification-using-K-Nearest-Neighbours

This is a classification task where we're given chemical composition of wines and we've to make prediction if the wine is fraud or legit.

In this, I've used K-Nearest Neighbour classifier model. I first read the .csv file using pandas pyhton library. I then check for any missing data. 

I then proceed to split the data into train and test. I use a loop to determine the best K value. I then use the best K value in the final model and make predictions based on that. I then use classification report to check the accuracy of the model and get accuracy score of 0.97.
