# Handwritten Digit Recognition using K-Nearest Neighbors (KNN)

This project aims to classify handwritten digits using the K-Nearest Neighbors algorithm. The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) from scikit-learn is employed for training and testing.

## Dataset

The MNIST dataset is a collection of 28x28 pixel grayscale images of handwritten digits (0 through 9), commonly used for benchmarking machine learning algorithms.

The dataset consists of 70,000 training images, each image is represented as a 28x28 matrix of pixel values, with each pixel ranging from 0 to 16, representing the intensity of the grayscale.

## Implementation

I used the scikit-learn library to:
1. Load the MNIST dataset.
2. Train a KNN classifier on the training data.
3. Evaluate the classifier's performance on the testing data.

## Results

After training the KNN classifier and evaluating its performance, I achieved an accuracy of 99.3% on the testing set.

## Real-World Applications

Handwritten digit recognition has numerous real-world applications, including:
- Automatic mail sorting in postal services
- Check digit recognition in banking and finance
- Handwritten address recognition in logistics and delivery services
- Digit recognition in OCR (Optical Character Recognition) systems
