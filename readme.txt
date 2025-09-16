What the project does,
  * Here is a deep learning model to predict whether person has diabetes or not when we provide some factors related to that disease. 

The dataset used,
  * Here i have uploaded the dataset that i have used for that. it is a csv file.

The Brief explanation of the process,
* Here i firstly used Pandas library to work with my dataset called diabetes.csv file. 
* Then after i divided my dataset into dependent and independent variables. Here the dependent variable is 'Outcome' column and another columns are the independent variable. So here I did not use any feature engineering techniques to select most valuable independent variables.
* Then after I used 'train_test_split' function to split my dataset for training and testing. So here I used 30% of data for the testing purpose.
* After that I imported 'TensorFlow' framework for creating the deep neural network and 'Keras' wrapper library that is work top of the TensorFlow for minimizing my code.
* Then after I imported Sequential(Dense) neural network, 'Dense' and 'Activation' layers for that neural network
*Then I created empty Sequential neural network and after that i added for the first layer as 'Dense' with 100 neurons and it's activation function is 'Relu(Rectified Leaner Unit)'. Also the second layer is 'Dense' but i used 50 neurons for that because i wanted to grab most important information from the first layer. It's activation function is also 'Relu'.Third layer is also 'Dense' with 25 neurons with 'Relu' activation functions. Final Layer is also the 'Dense' with one neuron but its activation function is 'Sigmoid' because here the final layer is the binary decision making layer. So my model's purpose is checking whether there is diabetes or not. So for that decision i wanted the 'Sigmoid' activation function. 
* Then after I used 'binary_crossentropy' formular to calculate loss and 'Adam' for the optimizer algorithm. 
* So then after I Trained the model with 75 epochs with those configurations.
* Model Accuracy-0.6926
