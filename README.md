# Churn-Modelling-using-Artificial-Neural-Network
Churn Modelling using Artificial Neural Network...DataSet From Kaggle.

Technologies used:
pandas: for reading dataset
matplotlib: for visualising the loss and accuracy
sklearn: for data preprocessing and accuracy score and confusino metrics
Tensorflow and keras:  for building Artificial neural network

Description:
Had input of 10 featues .. created first hidden layer (Dense)with units=6,activation=relu, second layer(dense) with units=6 and activation=relu, Third layer(Dense)
with activation=sigmoid and units=1


compiled with adam optimiser, loss='binary_crossentropy' as i have binary classification and metrics=accuracy

fit modle with batch size of 30 and 50 epochs.

added two graphs of accuracy/epoch and loss/epoch

and finilise project with accuracy score of 86.25%
.

