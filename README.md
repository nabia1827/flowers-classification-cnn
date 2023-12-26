# Flower Classification APP
An artificial intelligence application that uses a CNN to classify various types of flowers based on images provided by the user.
<div align="center">
  <img src="home.png" width="600">
</div>

<div align="center">
  <img src="lilies.png" width="600">
</div>

<div align="center">
  <img src="flowers.png" width="600">
</div>

## Introduction
This program provides a menu-based interface with two distinct options:
- Lily Classifier: Predict the type of lily based on user-input sepal and petal size, as well as the width separating the petal.
- Flower Image Classifier: Classify a flower from an image using a pre-trained CNN. The model has been trained on a variety of flowers, including roses, daisies, lilies, lavenders, and sunflowers.
The program has been developed in the Jupyter Notebook environment using the Python programming language.

## Features
- Lily classification using the Naive Bayes Machine Learning algorithm.
- Flower classification using a Convolutional Neural Network.
- User-friendly menu interface.
- Simple input requirements for lily classification.
- Image-based flower classification.

## Usage
### Lily Classifier:

- Run the program and select the Lily Classifier option.
- Input sepal size, petal size, and width of separation when prompted.
- The algorithm will predict the type of lily based on the provided inputs.
  
### Flower Image Classifier:
- Choose the Flower Classifier option.
- Upload an image of a flower when prompted.
- The CNN will predict the flower type based on the pre-trained model.

## Requirements
- os
- keras
- numpy 
- pandas
- tensorflow
- IPython
- cv2
- PyQt5
