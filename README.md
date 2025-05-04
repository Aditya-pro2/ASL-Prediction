# American Sign language (ASL) Prediction

<p align = "center"> <img src = "https://github.com/Aditya-pro2/ASL-Prediction/blob/main/Images/ASL.jpg" width = "800"> </p>

## Aim

This project aims to recognize what a person wants to convey using (American Sign Language) ASL hand gestures. The dataset contains 29 classes which comprises of the alphabets **A** to **Z**, **nothing**, **space** and **delete**.

## Contents of the Notebook

- Importing Libraries
- Importing the Dataset
  - Image Labels
  - Conversion of Images and Labels into NumPy Arrays
- Image Augmentation
  - Visualization of X and y
- Data Preprocessing
  - One Hot Encoding
  - Dimension Verification
- The CNN Model
  - Building the Model
  - Early Stopping
  - Model Compilation
  - Model Fitting
  - Plotting Accuracy
  - Plotting Loss
  - Results
  - Saving the Model
- Predictions
  - Actual Label vs Predicted Label
  - Confusion Matrix
  - Classification Report

## Model Used - Convolutional Neural Network (CNN)

A feed forward deep learning neural network designed for processing structured arrays of data such as images. Convolutional neural networks are very good at picking up on patterns in the input image, such as lines, gradients, circles, or even eyes and faces. It is this property that makes convolutional neural networks so powerful for computer vision. Unlike earlier computer vision algorithms, convolutional neural networks can operate directly on a raw image and do not need any preprocessing.

## Libraries Needed

- Tensorflow
- cv2
- glob
- matplotlib
- random
- math
- os
- numpy
- PIL
- scikit learn
- keras
- skimage

## CNN Model Results

<p align = "center"> <img src = "https://github.com/Aditya-pro2/ASL-Prediction/blob/main/Images/Model%20Accuracy.jpg" width = "800"> </p>
