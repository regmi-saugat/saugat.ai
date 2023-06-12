---
toc: true
layout: post
description: A blog post about Convolutional Neural Networks (CNNs)
categories: [markdown]
title: Convolutional Neural Network
---

# Convolutional Neural Networks

- Convolutional Neural Networks (CNNs) are one type of neural network that can be used to enable machines to visualize things and perform tasks such as image classification, image recognition, object detection, etc.
- CNN image classification takes an input image, processes it, and classifies it under specific categories.

**Let, us look Convolutional Neural Network structure**

![Image](https://github.com/regmi-saugat/saugat.ai/blob/master/images/CNN%20as%20Blackbox.png)

The CNN Box has different layers inside it, and each layer has a specific job in the convolutional neural network. These layers work together to understand and analyze complex visual or sequential data by breaking it down into smaller details.

![Image](https://github.com/regmi-saugat/saugat.ai/blob/master/images/Structure%20of%20CNNs.png)

In, Convolutional Neural Network (CNNs), the input image pass through a series of convolutional layers, pooling (down-sampling) layer, and fully connected layers and finally produces the output which can be a simple class or a probability of classes that best describes the images.

We want the computer to be able to differentiate between all the images it’s given. For that, the computer performs image classification by looking for low-level features such as edges, and curves, and building up to make extract concepts through a series of convolutional layers.

### **Why do we use Convolutional Neural Networks?**
- Feed Forward Neural Networks can learn a single feature representation of the image but in the case of complex images, neural networks fail to give better predictions. This is because it cannot learn pixel dependencies present in the image. Convolutional Neural Networks can learn multiple layers of feature representations of an image by applying different filters or transformations.
- In a Convolutional Neural Network (CNN), the total number of parameters that the network needs to learn is considerably less compared to a traditional multilayer network.

To capture and extract meaningful information from input data, we need something called Convolutional Operation.

Convolution Operation is a linear application of a smaller filter to a layer input that results in an output feature map. This operation helps to capture the patterns and spatial relationships within the input data and also helps to detect the various features like edges, textures, or shapes. Such features are learned during the training process while neural networks adjust the values of the kernel to optimize their performance on specific tasks. Thus, a convolutional operation is a tool that makes CNNs more powerful.

