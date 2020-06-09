# model.py
This file contains the Neural Network Model.

# predict.py

The **model_fn** function
  * Input
    * model_dir - The directory where the model is located.
  * Output
    * returns the loaded model.
 
The **input_fn** function
  * Input
    * serialized_input_data - The input data in a serialized form.
    * content_type - type of the input data (Eg.: CSV etc.,)
  
The **output_fn** function
  * Input
    * prediction_output - serialized prediction.
  * Output
    * string version of predicted output.
 
The **predict_fn** function
  * Input
    * input_data - input test data.
    * model - The neural network model.
  * Output
    * returns the predicted output.
    
    
 
