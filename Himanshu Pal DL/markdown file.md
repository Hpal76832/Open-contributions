# Convolutional Neural Network 
* Fully connected feedforward neural networks can be used to learn features and classify data, this architecture is generally impractical for larger inputs such as high resolution images.
* A convolutional neural network (CNN) is a type of artificial neural network used in image recognition and processing that is specifically designed to process pixel data. ... CNN have their “neurons” arranged more like those of the frontal lobe, the area responsible for processing visual stimuli in humans and other animals.
* Fully connected feedforward neural networks can be used to learn features and classify data, this architecture is generally impractical for larger inputs such as high resolution image.


## Pooling Layer
* Convolutional networks may include local and/or global pooling layers along with traditional convolutional layers. 
* Pooling layers reduce the dimensions of data by combining the outputs of neuron clusters at one layer into a single neuron in the next layer. 
* Local pooling combines small clusters, tiling sizes such as 2 x 2 are commonly used. 
* Global pooling acts on all the neurons of the feature map.
* There are two common types of pooling in popular use: max and average. 
* Max pooling uses the maximum value of each local cluster of neurons in the feature map,while average pooling takes the average value.


## Fully connected layers
* Fully connected layers connect every neuron in one layer to every neuron in another layer. 
* It is the same as a traditional multi-layer perceptron neural network (MLP). 
*The flattened matrix goes through a fully connected layer to classify the images. 
