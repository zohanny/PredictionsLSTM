# PredictionsLSTM
This notebook, using Keras / Tensorflow, allows to train models and make predictions using LSTM for stock markets retreived with the Yahoo API. 

Data can be scaled in two ways:  
1) Between 0-1
2) Diffence of the logarithms that captures the variation in ragers of previous day.

The model is preset to run predictions on the PSI, but you can change the 'ticker' to any stock / index under: "Loading data from Yahoo"

#### How-to:
1) Start by running all "Preliminary tasks" including "defining data functions".
2) Run "Linear Univariate model" OR "Diff(log) model"
3) On the predictions section run all code under "Defining methods for predictions"
4) Under Running Predctions run "Linear Model" OR "DiffLog Model
