# Blood-Cell-Image-Classification
Project related to the course of Artificial "Neural Networks and Deep Learning" (AN2DL) at POLIMI (polytechnic university of Milan)

## Introduction
This project was developed to solve an image classification problem as part of [First challenge of the course of Artificial Neural Networks and Deep Learning (AN2DL)](https://www.linkedin.com/posts/airlab-polimi_artificialneuralnetworks-deeplearning-imageclassification-activity-7266783804885803008-4nDc?utm_source=share&utm_medium=member_desktop).

## Goal
The challenge was to tackle a complex medical image classification problem: specifically, we had to develop an advanced model of a convolutional neural network capable of correctly identifying and classifying different types of blood cells.
As explained in the report (Report.pdf), the main challenge to face was the big difference between the dataset provided for the training ([Link Text](###Training set)) and the heavily corrupted private test set ([Link Text](###Test set))on which the model’s performance was assessed.

## Results
The model achieved 86% accuracy on private test set

## Final Grade
5.5/5.5 points

### Training set
The training set was made of 13759 96x96 RGB images (0,255) categorisied into 8 different classes.
8 samples randomly taken from each class of the training set.
![training set](/Training_set_image.png)

### Test set
80 samples randomly taken from the private test set (provided after the final evaluation)
![test set](/Test_set_image.png)
