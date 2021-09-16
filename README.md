# Nigerian-Food-Identification-project-with-Pytorch
Naming common Nigerian foods using Pytorch's ResNet9

# Introduction

The model was built with Pytorch ResNet9 architecture only with minor modifications. 

# Dataset

The model was trained on 300 images, 50 images each of 

- Jollof Rice
- Fried Rice
- Moimoi
- Pounded Yam
- Akara balls
- Amala and Ewedu

The dataset can be found [here](https://jovian.ai/akinremibunmi111/02-insurance-linear-regression)

# Preprocessing

Data transforms 

- Normalization 
- Data augmentation

![Preprocessing](https://drive.google.com/file/d/1hWoepfY4bQ3prQ0qsa7Go-uVsRE1S-ry/view?usp=sharing)

# Accuracy curve

![Preprocessing](https://drive.google.com/file/d/1VofP-wp6Ozsstd9IMgc8Xtce-LlpWBrR/view?usp=sharing)

# The Model

The ResNet9 architecture, as described in [this blog series](https://www.myrtle.ai/2018/09/24/how_to_train_your_resnet/) was used for this project.
![resnet-9](https://github.com/lambdal/cifar10-fast/raw/master/net.svg?sanitize=true)

### Now, this architecture has various aspect:

* The convolution block
* resnet block
* the output block

The convolution block contains conv2d, batch normalization and relu function. The resnet block contains two convolution blocks and the input added to it. The model has two resent blocks with two convolution blocks in between. The output block contains maxpool, flatten, dropout and linear function.

### To further improve this model,

- More data should be used
- Extracting important features could help
- Deeper neural network




