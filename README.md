# Gender-and-Age-Detection
Introduction:

This project aims to detect the gender and age of a person from an image using machine learning algorithms in Python. The project is implemented using the Scikit-Learn library, which is a popular machine learning library in Python.

Requirements:

To run this project, you need the following software:

Python 3.6 or higher

Scikit-Learn library (version 0.24.2 or higher)

NumPy library (version 1.19.5 or higher)

OpenCV library (version 4.5.2 or higher)

Model:

The machine learning model used for this project is a combination of two classifiers:

Support Vector Machine (SVM) classifier for gender detection

Multi-Layer Perceptron (MLP) classifier for age detection

The SVM classifier is trained on a set of features extracted from the input image, which include Local Binary Patterns (LBP) and Histogram of Oriented Gradients (HOG) features. The MLP classifier is trained on a set of features extracted from the input image, which include the raw pixel values of the image.

The final output of the model is a tuple of two values: gender (0 for male, 1 for female) and age (in years).

Credits:

This project is based on the following sources:

UTKFace dataset:

https://susanqq.github.io/UTKFace/

Age and Gender Classification using Convolutional Neural Networks: 

https://talhassner.github.io/home/publication/2015_CVPR

Gender and Age Classification using OpenCV:

https://www.pyimagesearch.com/2017/11/27/image-deep-learning-python/
