# Criminal-Prediction-using-Neural-Networks
This is a Project where the model predicted the chances of a person being a criminal or not not. With this Classification Model I i got a rank of (299/15000) TOP 2% of an HackerEarth Competition named "Predict The Criminals"


TOOLS USED:-

- The model is coded and run in Jupyter notebook Environment

- NO external tools have been used, the entire model is coded with Basic Python using Numpy Library for Vectorization.
  (Python3 and Numpy)
  
 
Data files:-
(present in "data" folder)

"train.txt"- Contains the original train dataset with 71 columns which are arranged in Ascending order,
             and the "PERID" column Removed.
             
"test.txt"- Contains the original test dataset with 70 columns which are arranged un Ascending order,
            and the "PERID"column is removed.

Source File:-

- The source file has been trained on a Jupyter Notebook Environment.

- I have used an "Artificial Neural Network" approach to solve this problem.

- Architecture:-

  -> The model i have traoined is a 5 layered Neural Network with one input layer, 3 hidden layer and one output layer.
  
  -> All the Hidden layers are RELU activated while the output layer with Single Neuron in SIGMAID activated.
  
  -> Mini-Batch Gradient descent is implemented with mini-batches of 128 entries.
  
  -> ADAM Optimization is implemented with Betaa1=0.9 and Beta2=0.999
  
  -> The Learning Rate is set at 0.001 and the Model is trained for 620 Iterations.

- Results:-
  -> Recieved a Training Set accuracy of 95.7566%
  -> And a Validation set accuracy of 95.12%

THANK YOU...
