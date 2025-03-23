# Handwritten_digit_recognition
Handwritten digit recognition on the MNIST dataset

# What is MNIST?
1. Set of 70,000 small images of digits handwritten by high school students and employees of the US causes Bureau.
2. All images are labeled with the respective digit they represent.
3. MNIST is the hello world of machine learning. Every time a data scientist or machine learning engineer makes a new algorithm for classification, they would always first check its performance on the MNIST dataset.
4. There are 70,000 images and each image has 28*28 = 784 features.
5. Each image is 28*28 pixels and each feature simply represents one-pixel intensity from 0 to 255. If the intensity is 0, it means that the pixel is white and if it is 255, it means it is black.

Let’s move on to our IDEs, and see how productively we can use the MNIST dataset. I have also attached my Jupyter notebook below. You can follow that while we proceed.

1. First of all, import all the libraries required. We will import the fetch_openml from the sklearn.datasets library.
2. Create a variable mnist, and store in it the mnsit_784 dataset from the featch_openml And you can further print and see the contents of this mnist dataset. You can see its keys, its data, its corresponding labels, and more.

# fetching dataset
from sklearn.datasets import fetch_openml
import matplotlib
import matplotlib.pyplot as plt
import numpy as np
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import cross_val_score

mnist = fetch_openml('mnist_784')





