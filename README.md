# Image_Classification
This repository contains an image classification project using TensorFlow and Keras. The project aims to classify images of cats and dogs using a convolutional neural network (CNN).

# Model Architecture
The model architecture consists of a simple convolutional neural network (CNN) with the following layers:

Conv2D layer with 32 filters and a 3x3 kernel
MaxPooling2D layer with a 2x2 pool size
Conv2D layer with 64 filters and a 3x3 kernel
MaxPooling2D layer with a 2x2 pool size
Flatten layer
Dense layer with 128 units and ReLU activation
Dense layer with the number of classes (2 in this case) and sigmoid activation

# Results
The model is to be trained for 20 epochs with a batch size of 32. The training and validation accuracy and loss are printed during training. After training, the model is evaluated on the test set, and the test accuracy and loss are printed.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
