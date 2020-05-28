# RCNN-A-Better-Model-for-Biological-Object-Recognition
Implements the part of research paper: https://www.frontiersin.org/articles/10.3389/fpsyg.2017.01551/full.

I have used the Cifar-10 dataset to compare the performaces of recurrent convolutional neural networks with bottom-up (B), lateral (L), and top-down (T) connections with that of the conventional CNN(feed-forward) model. Since comparing the feedforward models with the recurrent models is not fare enough as recurrent models will have more number of parameters than the feedforward models. To overcome this issue I have used two varients of feedforward models (BF) by increasing the size of the kernel and (BK) by incresing the number of the filters.

![](Images/Models.JPG)

# Prerequisite
* Tensorflow 2.0
* Keras
* Numpy
* Matplotlib

# Dataset
Cifar10 Dataset with different variations
* Without Noise
* With Noise level 1
* With Noise level 2
![](Images/Dataset.JPG)

# Using Code
Models folder contains the code for both Without Noise and With Noise. In case of With Noise, you need to change the level of the noise (1 or 2) while adding it to the original dataset. And same applies for the names while saving model weights or even the predictions.

# Results
Classification Increases as the noise level increases 
![](Images/Error.JPG)
