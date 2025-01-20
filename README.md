# Image_Classifier

Man vs Monkey Image Classification
This project implements an image classification model to distinguish between images of humans (Man) and monkeys using a neural network built with Keras and TensorFlow. The model is trained on a custom dataset of images, and uses data augmentation and a convolutional architecture for classification.

Features
Image Classification: Classifies images into two categories: "Man" and "Monkey".
Data Augmentation: Applies random transformations to the training data, enhancing the model's ability to generalize.
Xception-like Network Architecture: A custom deep learning model inspired by Xception, built with separable convolutions for efficiency.
Corrupted Image Removal: Automatically filters out corrupted images before training.