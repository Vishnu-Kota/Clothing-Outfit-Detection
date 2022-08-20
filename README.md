# Clothing Outfit Detection
 Outfit Detection model built using ResNet 50 and Fastai.
 
 # RestNet50
 The ResNet-50 model consists of 5 stages each with a convolution and Identity block. Each convolution block has 3 convolution layers and each identity block also has 3 convolution layers. The ResNet-50 has over 23 million trainable parameters. The fundamental breakthrough with ResNet was it allowed us to train extremely deep neural networks with 150+layers successfully. Prior to ResNet training very deep neural networks was difficult due to the problem of vanishing gradients.

ResNet first introduced the concept of skip connection. The concept is stacking convolution layers together one after the other. We still stack convolution layers as before but we now also add the original input to the output of the convolution block. This is called skip connection
![image.png](https://miro.medium.com/max/1400/1*hEU7S-EiVqcmtAlj6kgfRA.png)
![image.png](https://miro.medium.com/max/1140/1*D0F3UitQ2l5Q0Ak-tjEdJg.png)
