# Hybrid transfer learning for image classification (COVID-NonCOVID)
The project is using QML to do medical sensing and disease diagnosis by imaging processing...

This is an example of a hybrid network for image classification, developed according to the classical-to-quantum transfer learning scheme presented in [1].

This notebook is inspired by the official PyTorch tutorial on transfer learning by Sasank Chilamkurthy [2].

The starting point is a convolutional neural network—ResNet18, which is pre-trained on the public ImageNet dataset. Specifically, we focus on two classes of insect images: COVID and NonCOVID.

A graphical scheme of our hybrid classical-quantum model is represented in the following figure.

![image](https://user-images.githubusercontent.com/78730355/188714653-b2cc8e84-8487-42a0-ab54-39c4cd029389.png)
