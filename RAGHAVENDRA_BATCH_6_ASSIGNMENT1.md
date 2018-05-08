 ## Convolution
   Convolution used in the context of Aritificial Neural Networks is extracting information from a particular input and passing it on to the upper layers of the neural net. This is similar to the neurons responding to a visual or an external stimuli, where each part of the stimulus is processed by a particular neurons and results propogated to the upper layers to make sense of the stimulus as a whole. 
   Convolutions currently used in ANNs are 3* 3, 5* 5, 7* 7 and recently 1* 1. In processing an image of size 7 * 7 for eg, a 3 * 3 convolution will yield us a 5 * 5 feature map as seen in the image below. 
 
 ![3 * 3 convolution example](https://adeshpande3.github.io/assets/Stride1.png)
  
  ## Feature maps
   Output of each convolution layer in a neural net is called a feature map. Filters act on top of the feature to extract the results required. 
