
# Overview of Image Classification Models

## Pre-trained Models
### 1. **ResNet**
> [!TIP]
> More details about ResNet can be found at:\
> [ResNet: PyTorch](https://pytorch.org/hub/pytorch_vision_resnet/?utm_source=chatgpt.com)
> and [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)

#### **Architecture:**
Convolutional Neural Network (CNN) architecture
  
ResNet is a short name for Residual Network. As the name suggests, it adds a shortcut/skip connection to the network. This helps in solving the problem of vanishing gradients. **The skip connection skips one or more layers and connects the output of the layer to a non-adjacent layer**.

Resnet18, Resnet34, Resnet50, Resnet101, Resnet152 are the most popular versions of ResNet.

![ResNet architecture](https://pytorch.org/assets/images/resnet.png)

#### **Key Features:**
ResNet is one of the most popular pre-trained models. It is widely used in image classification, object detection, and feature extraction. It has been trained on the ImageNet dataset and has achieved state-of-the-art performance on various tasks.

> [!NOTE]
> - An ensemble ResNet residual nets achieves 3.57% error on the ImageNet test set. This result won the 1st place on the ILSVRC 2015 classification task.
> -  ResNet-152 achieves 5.71% (10-crop) top-5 error on the ImageNet test set.

### 2. **VGG**

### 3. **MobileNet**

## Hybrid Models (CNN + Attention Mechanisms)


