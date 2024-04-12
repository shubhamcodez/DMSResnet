# DMSResNet: Distilled MixUp Squeeze Residual Network

This repository contains a submission for NYU ECE-GY 7123 Deep Learning S24 Kaggle Competition titled "Distilled MixUp Squeeze Residual Network", authored by Shubham Singh, Inder Khatri, and Xu Zhou. 

## Overview
We propose a ResNet model evaluated on the CIFAR-10 dataset trained using various techniques such as mixUp data augmentation, Squeeze-and-Excitation (SE) blocks, and knowledge distillation.

## Model Specifications
- **GPU:** P100 2 hours
- **Batch Size:** 128
- **Epochs:** 200
- **Dropout:** 0.1
- **Validation Accuracy:** 96.3% 
- **Testing Accuracy:** 86.9%
- **Optimizer:** Stochastic Gradient Descent
- **Learning Rate:** 0.1

### Architectures
- **Teacher model:** ResNet50
- **Student model:** Custom model with a ResNet containing 4.6 million parameters, mixUp, and dropout of 0.1.

## Weight Files
The `weights` folder contains 2 weight files: 
1. Weights of the trained ResNet50 model.
2. Weights of our final model. 

## Usage
1. Run the `ResNet50.ipynb` notebook to train ResNet50.
2. Use weights from ResNet50 to train a distillation notebook containing a smaller model.

## Authors
- Shubham Singh
- Inder Khatri
- Xu Zhou
