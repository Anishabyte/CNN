# **CONVOLUTION NEURAL NETWORK**

Convolutional Neural Network (CNN) is the extended version of artificial neural networks (ANN) which is predominantly used to extract the feature from the grid-like matrix dataset. 

## **CNN ARCHITECTURE**

Convolutional Neural Network consists of multiple layers like the input layer, Convolutional layer, Pooling layer, and fully connected layers.
* The Convolutional layer applies filters to the input image to extract features
* The Pooling layer downsamples the image to reduce computation
* Activaltion layer add non linearity to the network ,it will apply an element wise activation function to the output of the convolution layer.
* The fully connected layer makes the final prediction. The network learns the optimal filters through backpropagation and gradient descent.

# **What is Done in this Repository**

* first  downloaded the CIFAR 10 dataset having 10 classes
* loading the data into certain batch size using torch.utils
*  Visualizing the images
*  Applying multiple Convolutional layer
* * Applying Lenet (LeNet is a foundational convolutional neural network (CNN) comprising convolutional, pooling, and fully connected layers, designed for image classification and handwritten digit recognition.)
  *  used tanh as Activation Function
* Training on GPU
* Done simple Visualization to visualize the 1 st layer i.e the Convolutional layer where we saw how the filters are applied on each channels in thhe 1 st layer.
