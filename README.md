# CNN-MobileNet-CIFAR10
This repository contains the implementation of MobileNet network architecture on CIFAR10 dataset using Keras &amp; Tensorflow in Python. Using this model, I have achieved 92% training accuracy and 84% test accuracy on CIFAR-10 image classification dataset.

In Convolutional Neural Networks and Image Classification methods, the MobileNet architecture was designed for mobile vision applications which required less computational resources with reasonable accuracy compared to other networks. To do that, MObileNet has some hyperparameters which made it a good fit for the devices having less computational resources. I have written a paper on MobileNet design architecture, width and resolution multipler hyperparameters and some otehr tweeks in the model architecture.

I have done some changes in the model architecture to make sure the data is fit into internal memory (input feature maps, filter coefficients and output feature maps). The limit of internal memory was 1 MB. 

The paper describes the changes and training methods I have used in this model.
