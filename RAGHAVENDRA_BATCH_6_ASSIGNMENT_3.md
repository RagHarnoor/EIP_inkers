
### Convolution

1. Convolution used in the context of Aritificial Neural Networks is an operation used for extracting information from a particular input and passing it on to the upper layers of the neural net. This is similar to the neurons responding to a visual or an external stimuli, where each part of the stimulus is processed by a particular neurons and results propogated to the upper layers to make sense of the stimulus as a whole.
2. Convolutions currently used in ANNs are 3* 3, 5* 5, 7* 7 and recently 1* 1. In processing an image of size 7 * 7 for eg, a 3 * 3 convolution will yield us a 5 * 5 feature map as seen in the image below.
3. Output of each convolution layer in a neural net is called a feature map. Filters act on top of the feature to extract the results required. If a 400 * 400 image is convolved to get a 10 * 10 feature map using 3 * 3 convolution, then we would have 195 feature maps! A feature map when acted upon by a activation function, it becomes a neuron.

Diffrent kinds of convolution currently being used in neural nets are:
* **1x1 Convolution** - Used as a feature merger or feature merger. 
* **Cx1, 1XC Convolutions** - Winegrad convolution - Used because of the minimum loss and faster computations, with convolution of 7 * 1 and 1 * 7 we get a receptive feed of 7 * 7, which would need 3 3 * 3 convolutions, it is said to be 7.2 times faster than regular convolutions. 
* **Spacial convolutions** - Used to extract diffused features



