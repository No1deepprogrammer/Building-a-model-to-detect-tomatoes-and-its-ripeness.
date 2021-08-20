# Building-a-model-to-detect-tomatoes-and-its-ripeness.  
In this project I have solved detection problem using deep learning, where our goal is to detect tomato and its ripeness. For doing this project there are several steps-

    Step 1 Install all required library and dependency
    Step 2 collection of dataset
For doing this project I have download the tomato data from google.
   
   Step 3 Splitting of dataset
I have split the whole dataset into two part training_set and test_set and each have two sub-folder Ripeness tommato and another is Without Ripeness.
  
  
  Step 4: Proposed Model
  
Here I have used the Convolution Neural Network to develop this given project. CNNs have wide applications in image and video recognition, recommender systems
and natural language processing. Convolutions are frequently used in image processing, which is also why they were introduced to visual tasks in the field of deep
learning. They allow learning local patterns in the data instead of treating the input features in a global manner like dense layers do. Convolutional neural networks
(CNNs) are a specific type of ANN that uses an operation called convolution in at
least one of their layers. 

  Step 5:  Training, Validation, and Testing Sets

The data was split into three subsets of which each was applied for learning process
of the model (training, validation, and testing)[1]. The training set is commonly
the largest of the three and contains the data that is applied to the actual learning
process. It’s the only portion of the data the network will try to recognize the
pattern and learn the target image. The validation data is used to regularly measure
the performance of the model and check whether overfitting occurs or not. If the
accuracy of the validation set drops below the results of the training data, the
network is starting to memorize the data it knows rather than generalizing on the
concept. The third subset is referred to as the testing data. In contrast to the
validation set, it’s only used once in the very end, to give a final score. The idea
is that by building a model based on the validation results a certain amount of
information bleed occurs, where the network will implicitly learn from the validation
data.

    Step 6: Result
    
The results in this project are based on data the network has been trained with.
For building a model to detect tomato with its ripeness and results are obtained from different Ripeness tomato and Without Ripeness. The methodology is applied on 72 tomatoes images from which 56
tomatoes are used for training and 16 tomatoes are used for testing.    


     
    


  
  

