# Image Classification with Convolutional Neural Networks

In the notebook in this repo, I train a simple convolutional neural network (CNN) in PyTorch to classify images using Zalando's [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). This dataset consists of a 70,000 grayscale images of 10 categories of pieces of clothing 

I'm training a simple neural network consisting of two convolutional layers with two pooling layers followed by three fully connected layers. This network achieves a prediction accuracy of 90% on the test set. It does have some trouble however with distinguishing between two very similar classes: Shirts and t-shirts. 

I originally wrote this notebook for myself as as reference for future projects with PyTorch.
