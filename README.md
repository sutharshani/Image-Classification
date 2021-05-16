# Image Classification using Keras and Tenserflow
It is an image classification project work. Image classification comes under the computer vision project category and is mostly used in digital image analysis. We can apply image classification for both supervised classification and unsupervised classification. In the supervised classification, we do train model on target class to classify the class correctly in new samples. But we group the samples the cluster of images with similar properties in unsupervised classification. The goal of this project is to work on various approaches to solve the classification problem. I will also compare the results from the models to find an algorithm that works efficiently and produces better results.

# Table of Contents
1. [Introduction](#introduction)
2. [Data Background](#data-background)
3. [Prerequisite](#prerequisite)
4. [Project Status](#project-status)
5. [Versioning](#versioning)
6. [Authors](#authors)
7. [Acknowledgement](#acknowledgement)
8. [Reference](#reference)

## Introduction
Image classification performs tasks of pattern recognition and objects classification in Computer Vision.  We construct machine learning models that analyze the image to identify the class of the image. The class is nothing, but a label associated with the category, for example, automobile, truck, cat, dog, etc. We can take a real-time example of image classification can be 'tagging' in social media websites. When we upload an image with people in them and tag them in the picture. They do have that information and use ML models to recognize the person in the image in the future.

It seems easy for us to classify images, but it is quite a difficult task for machines. We need to take help from deep learning models to perform this task. 
Image classification work relies on pixel data. So, we need to break down the image into a set of pixels to carry this work.  Another issue with image classification is that images can have different sizes, backgrounds, pose, angle, color, and so on many more similar variables.

Deep learning models have shown some great results for image processing-related problems. Deep learning models do use multiple layers of neural networks for their processing. There are many types of neural networks that are used in different classification and regression modeling. From my research, I found that deep learning CNN models do work best for Image classification modeling. The nodes in the hidden layers do not always share their output with every node in the next layer. 

I have started with describing the input dataset in this paper, and then I discussed categories of images present in the dataset. After that, I visualized sample data and then constructed different models to classify the image. I worked on a different technique to fix the overfitting problem that happens with Deep learning models. I tried methods like dropout regularization, weight regularization, and data augmentation. I did try different combinations of these regularization methods as well. I found that data augmentation works better than other regularization methods based on results from this project.  


[back to top](#table-of-contents)
## Data Background
The CIFAR-10 dataset consists of 60000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The good thing about the data is that the dataset is already well prepared, so I do not have to work on filtering out the images otherwise, I would have needed to follow a different approach to work on this problem.

This dataset has images from 10 different classes airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. 
All the classes are mutually exclusive, and there is no overlapping. For example – ‘Automobile’ includes vehicles like sedan, SUV and ‘Truck’ includes big trucks. Pickup trucks are not present in this dataset.


[back to top](#table-of-contents)
## Prerequisite
You will need the following applications to execute this project-

* Python 3 (or Anaconda distribution with Python 3)
* Jupyter or any other notebook
* Tensrflow
* Keras

[back to top](#table-of-contents)

## Project Status
Currently I have completed the project with limited resource but I plan to explore more in future \
[back to top](#table-of-contents)

## Versioning
Git is used for project versioning. \
[back to top](#table-of-contents)

## Authors
Shani Kumar \
[back to top](#table-of-contents)

## Acknowledgement
In this project I learned how do we work with image data and build model for image classification. While working on optimizing model, I learned different techniques which we can use to resolve model overfitting and underfitting issues. I learned how do we apply dropout regularization, weight delay and data augmentation. If we build CNN model with good research, it can produce results with excellent accuracy.
[back to top](#table-of-contents)

## Reference
1.	https://www.cs.toronto.edu/~kriz/cifar.html
2.	D. Lu & Q. Weng (2007) A survey of image classification methods and techniques for improving classification performance, International Journal of Remote Sensing, 28:5, 823-870, DOI: 10.1080/01431160600746456
3.	Lei Wang, Yanning Zhang, Runping Xi, & Lu Ling. (2019). Natural Image Classification based on Multi-Parameter Optimization in Deep Convolutional Neural Network. International Journal of Performability Engineering, 15(9), 2515–2521. https://doi-org.ezproxy.bellevue.edu/10.23940/ijpe.19.09.p25.25152521
4.	Yoon, Y. C., Park, S. Y., Park, S. M., & Lim, H. (2020). Image classification and captioning model considering a CAM‐based disagreement loss. ETRI Journal, 42(1), 67–77. https://doi-org.ezproxy.bellevue.edu/10.4218/etrij.2018-0621


[back to top](#table-of-contents)
