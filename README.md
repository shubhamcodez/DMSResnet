# DMSResNet: Distilled MixUp Squeeze Residual Network

This repository contains the code implementation of the paper titled "DMSResNet: Distilled MixUp Squeeze Residual Network", authored by Shubham Singh, Inder Khatri, and Xu Zhou. The paper proposes a novel architecture for image classification tasks, optimized for memory efficiency while maintaining high accuracy rates. The model is evaluated on the CIFAR-10 dataset using various techniques such as mixUp data augmentation, Squeeze-and-Excitation (SE) blocks, and knowledge distillation.

## Abstract

The paper introduces a Distilled MixUp Squeeze Residual Network (DMSResNet) architecture tailored for image classification tasks, particularly in resource-constrained environments. 
The model incorporates advanced techniques like mixUp data augmentation, SE blocks, and knowledge distillation to achieve high accuracy rates on the CIFAR-10 dataset within a stringent parameter 
constraint of 5 million. The proposed architecture showcases remarkable accuracy and generalization capabilities, making it suitable for real-world applications where computational resources are limited.

## Usage
Run the Resnet50 notebook to train Resnet50. <br>
Use weights from Resnet50 to train a distillation notebook containing a smaller model. 
