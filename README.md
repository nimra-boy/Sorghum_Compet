# Sorghum_Compet

## Table of Contents
1. [General Info](#general-info)
2. [Overview](#overview)
3. [Model](#model)
4. [Technologies](#technologies)
5. [Data](#data)

### General Info
***
Kaggle competition: https://www.kaggle.com/competitions/sorghum-id-fgvc-9

Kaggle link: https://www.kaggle.com/code/arminatc/sorghum-fastai

Github link: https://github.com/nimra-boy/Sorghum_Compet

### Overview
***
This Kaggle competition aims to predict a cultivar based on the image of a plant, the goal being to identify the different crop varieties.

### Model
***
The method chosen to answer this problematic is a deep learning model named Resnet50. ResNet, for Residual Networks, is one of the most popular deep neural networks powerful who got fantastic performance in the ILSVRC classification challenge 2015. There are many variations of the ResNet architecture, i.e. the same concept but with a different number of layers. For this project I tested those with 34 and 50 layers.

### Technologies
***
A list of technologies used within the project:
* [python](https://www.python.org/)
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [seaborn](https://seaborn.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [fastai](https://www.fast.ai/)
* [pytorch](https://pytorch.org/)

### Data
***
https://www.kaggle.com/competitions/sorghum-id-fgvc-9/data

The Sorghum-100 dataset consists of 48,106 images and 100 different sorghum cultivars grown in June of 2017 (the images come from the middle of the growing season when the plants were quite large but not yet lodging -- or falling over).

Each image is taken using an RGB spectral camera taken from a vertical view of the sorghum plants in the TERRA-REF field in Arizona.
