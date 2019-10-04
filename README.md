# Elections-Data
Machine learning, Decision tree model on election data 


First, I selected relevant features for predicting election data that I read in from the .csv. After relevant features are selected, we want to try to predict the parties. I used a K means clustering algorithm to create the relevant clusters. After the clusters were created, I used sklearn to train, test, split the data. I then used GridsearchCV to find the best model for each cluster. Then, I fit each model, predict the outcome of the model on the test data, and calculate the error for each model. 
