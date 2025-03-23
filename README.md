# Handwritten_digit_recognition
Handwritten digit recognition on the MNIST dataset

# Project Summary: Handwritten Digit Recognition Using MNIST Dataset
This project focuses on handwritten digit recognition using the MNIST dataset, which consists of 70,000 grayscale images of digits (0-9), each represented as a 28x28 pixel image. The primary goal of this project is to build a machine learning model that can accurately classify handwritten digits.

# Key Steps in the Project:
1. Data Loading & Exploration:
  - Fetched the MNIST dataset using fetch_openml() from sklearn.datasets.
  - Visualized sample images using matplotlib to understand the data structure.

2. Data Preprocessing:
  - Split the dataset into training (60,000 images) and testing (10,000 images) sets.
  - Converted labels to integer format and reshaped the images into a suitable format.
  - Applied shuffling to randomize the training data.

3. Model Training:
  - Implemented a Logistic Regression classifier to detect if an image is digit ‘2’ or not.
  - Used binary classification, setting labels as True for digit ‘2’ and False for all other digits.
  - Trained the model using clf.fit(x_train, y_train_2).

4. Model Evaluation:
  - Predicted a sample image and verified its classification.
  - Used cross-validation (cross_val_score) to assess model accuracy.
  - Achieved an accuracy of 97.8%, demonstrating strong classification performance.

# Conclusion
The Logistic Regression model successfully recognized handwritten digits with high accuracy (97.8%), proving that it is a suitable approach for this classification task. However, accuracy alone is not always the best metric—precision, recall, and F1-score should be considered for further evaluation.

Future improvements could include:
  - Trying more advanced models like Support Vector Machines (SVM) or Neural Networks.
  - Implementing deep learning techniques (e.g., CNNs) for better feature extraction.
  - Exploring hyperparameter tuning to improve the model's performance further.

This project provided valuable insights into computer vision, image processing, and machine learning fundamentals, making it an excellent beginner-friendly project for data scientists. 🚀





