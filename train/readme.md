# model.py

This file contains the neural network model.

# train.py

The **model_fn** method implements the neural network model in the model.py file and returns the model. 

The **_get_train_data_loader** method.
  * Input 
    * training data and batch size.
  
  * returns
    * The training data in batches according to the batch size mentioned in the input.
    
The **train** method.
  * Input
    * model - the neural network model.
    * train_loader - the training data in batches.
    * epochs - Number of epochs
    * optimizer - An optimizer to decrease the loss.
    * loss_fn - A loss function to calculate the loss.
    * device - where the model should run.

The **main** method.
  * This method contains the SageMaker Parameters, Model Parameters, Training Parameters.
  * Along with these, It selects the device to run, Loads the training data, Builds the model, trains the model and saves the parameters
