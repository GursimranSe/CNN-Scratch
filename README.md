# **Convolutional Neural Network from Scratch in Python**

This repository contains a Python implementation of a simple Convolutional Neural Network (CNN) built entirely using the NumPy library. The code defines core CNN layers like Convolution2D and MaxPooling, and demonstrates their usage in a basic CNN architecture.

**Requirements**
NumPy (pip install numpy)

**Code Structure :**

  Implements the Conv2D class for 2D convolutional layers.
  
  Implements the MaxPooling class for downsampling feature maps.
  
  Defines a simple CNN architecture using Conv2D and MaxPooling layers


**Understanding the Code**
1. Conv2D class:
   
Initializes a convolutional layer with hyperparameters like input/output channels, kernel size, padding mode, and activation function.

  Performs the forward pass:
  
  Handles padding (optional).
  
  Calculates output dimensions based on padding.
  
  Iterates over each output channel, performing element-wise multiplication between weights and input regions, followed by summation and bias addition.
  
  Applies the chosen activation function (ReLU or sigmoid).
  
2. MaxPooling class:
   
   initializes a max pooling layer with a specified pool size.

   Performs the forward pass:
   
     Calculation output dimensions based on pool size.
   
     Iterates over each output channel, extracting regions of the input and taking the         maximum value within each region.

   
3. SimpleCNN class:
   
   Defines a simple CNN architecture by initializing instances of Conv2D and MaxPooling layers.
   
Implements the forward pass:

  Sequentially passes the input data through each layer in the defined order.
   

