# DeepLearningApplications
A future stock price prediction model was trained using a multilayer recurrent neural network. 
For this exercise, the share price of each day of the month of January is predicted using the information from the last 60 days. 
To avoid overfitting in the training of the model, a Dropout regularization was added in each hidden layer of the neural network. 
Due to the good results obtained in previous experiments, the "adam" optimizer and the batch size = 32 were used.
Below is a comparison between the predictions made with the RNN model and the actual prices of the shares during the month

![RNNPredictor](https://github.com/Andremoreno98/DeepLearningApplications/assets/72787477/fe93a5cd-7505-4028-97e1-a2d62be1d922)
