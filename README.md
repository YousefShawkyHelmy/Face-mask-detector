# Face Mask-detector

This repository contains code for a multi Face Mask detection system using deep learning.
It can detect whether a person or more is wearing the mask or not.


## Dataset

The dataset used for training and evaluation is created by [Jessica Li](https://www.kaggle.com/jessicali9530), which consists of 12,000 images of people with and without face masks. The dataset is divided into training, validation, and test sets.
You can dowload it from here [here](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset) .


## Model Architecture

The model used for Face detection, is the [ Haar cascade classifier](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html), originally known as the Viola-Jones Face Detection Technique, which is one of the most popular object detection algorithms for detecting faces in images or real-time video.
You can dowload it from [here](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml).


The model architecture used for face mask detection is based on the ResNet50 convolutional neural network. The pretrained ResNet50 model is used as the base, with additional layers added on top for classification.
