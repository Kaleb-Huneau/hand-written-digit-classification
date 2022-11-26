Here is a small project where I solved the MNIST problem while learning about machine learning.

A baseline was established by solving the problem using a fully connected neural network with each pixel as an input, one hidden layer with 128 neurons, and an output vector. The output is a probability vector where the index of maximum value in the vector corresponds to the prediction. 

Following this, the image was compressed to 14 x 14 pixels and run through the same network with the only difference being the input shape. That means the compressed network had 196 input pixels as opposed to 784 input pixels. The compressed model has 26,506 trainable parameters, and the original model has 101,770.  

Both networks were trained for 10 epochs and it was found that the compressed network ran faster with similar accuracy. This shows how combining features in machine learning can lead to better model efficiency through reduced training time. 
