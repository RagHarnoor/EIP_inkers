# Raghavendra Harnoorkar - Batch 6 - Assignment 1

## Convolution
   1. Convolution used in the context of Aritificial Neural Networks is an operation used for extracting information from a particular input and passing it on to the upper layers of the neural net. This is similar to the neurons responding to a visual or an external stimuli, where each part of the stimulus is processed by a particular neurons and results propogated to the upper layers to make sense of the stimulus as a whole. 
   2. Convolutions currently used in ANNs are 3* 3, 5* 5, 7* 7 and recently 1* 1. In processing an image of size 7 * 7 for eg, a 3 * 3 convolution will yield us a 5 * 5 feature map as seen in the image below. 
   3. Output of each convolution layer in a neural net is called a feature map. Filters act on top of the feature to extract the results required. If a 400 * 400 image is convolved to get a 10 * 10 feature map using 3 * 3 convolution, then we would have 195 feature maps! A feature map when acted upon by a activation function, it becomes a neuron. 
   
 
 ## Receptive Field
 * Receptive field refers to the number of pixels or units seen/processed by a layer direclty or indirectly. Each neuron/feauture map processes data only seen by it's receptive feed. 
 * Local receptive field refers to the nubmer of pixels a layer/feature map sees of the layer immidiately below it. In the image below, the local receptive field of the 5 * 5 layer is 7 * 7 i.e, 49. 
 * Global receptive field refers to the number of pixels looked at by the top most layer in the neural network. If a 400 * 400 image is convolved 200 times using 3 * 3 convolution to yield a 1 pixel. Then the Global receptive field will be 400 * 400 whereas the local receptive field will be the number of pixels in the layer below it.
  
    
 ![3 * 3 convolution example](https://adeshpande3.github.io/assets/Stride1.png)
  

