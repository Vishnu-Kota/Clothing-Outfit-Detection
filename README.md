# Clothing Outfit Detection
 Outfit Detection model built using ResNet 50 and Fastai.
 
 # RestNet50
 The ResNet-50 model consists of 5 stages each with a convolution and Identity block. Each convolution block has 3 convolution layers and each identity block also has 3 convolution layers. The ResNet-50 has over 23 million trainable parameters. The fundamental breakthrough with ResNet was it allowed us to train extremely deep neural networks with 150+layers successfully. Prior to ResNet training very deep neural networks was difficult due to the problem of vanishing gradients.

ResNet first introduced the concept of skip connection. The concept is stacking convolution layers together one after the other. We still stack convolution layers as before but we now also add the original input to the output of the convolution block. This is called skip connection
![image.png](https://miro.medium.com/max/1400/1*hEU7S-EiVqcmtAlj6kgfRA.png)
![image.png](https://miro.medium.com/max/1140/1*D0F3UitQ2l5Q0Ak-tjEdJg.png)

# Fastai
fastai is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches. It aims to do both things without substantial compromises in ease of use, flexibility, or performance. 

The model is able to recognise, identify and detect various clothing items
![image.png](https://user-images.githubusercontent.com/65905342/185755725-0f61bcf0-d28b-4e0f-90ab-c777f0da73c9.png)
