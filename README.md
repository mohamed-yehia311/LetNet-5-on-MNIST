# MNIST Digit Classification using LeNet-5

This project utilizes the LeNet-5 architecture to build and optimize a Convolutional Neural Network (CNN) for digit classification using the MNIST dataset. The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9).

## Project Overview

- **Dataset**: MNIST, consisting of 60,000 training images and 10,000 test images. Each image is 28x28 pixels.
- **Architecture**: LeNet-5, a pioneering CNN architecture known for its effectiveness in image recognition tasks.
- **Objective**: Achieve high accuracy in classifying handwritten digits.

## Model Architecture

The LeNet-5 architecture comprises:

1. **Input Layer**: 28x28 grayscale images.
2. **Convolutional Layers**: Extracts features from the images.
3. **Pooling Layers**: Reduces the dimensionality of the features, retaining the most important information.
4. **Fully Connected Layers**: Performs the final classification based on the features extracted.
5. **Output Layer**: Uses softmax activation to classify the input image into one of the 10 digit classes.

## Hyperparameter Tuning

To optimize the performance of the LeNet-5 model, we employed Keras Tuner for hyperparameter optimization. The following hyperparameters were tuned:

- **Learning Rate**: Controls the step size in gradient descent updates.
- **Batch Size**: Number of training examples utilized in one iteration.
- **Epochs**: Number of times the entire training dataset is passed through the network.

## Results

After extensive experimentation with different hyperparameter combinations, the optimized LeNet-5 model achieved an impressive accuracy of **99.3%** on the MNIST test set. This result demonstrates the effectiveness of the LeNet-5 architecture and the importance of precise hyperparameter tuning in achieving near-perfect classification results.

## Conclusion

This project showcases the capability of classic neural network architectures like LeNet-5, combined with modern hyperparameter optimization techniques, to deliver outstanding results in fundamental computer vision tasks. The success of this approach in digit classification tasks paves the way for further exploration into more complex image recognition challenges.
