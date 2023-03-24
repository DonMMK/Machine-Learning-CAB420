Design/select a DCNN architecture:
a. Research existing deep convolutional neural network architectures or design your own.
b. Consider the size of the training data and computational resources when selecting or designing the network architecture.

Train a model from scratch, using no data augmentation:
a. Load the training data (Q3/q3 train.mat) into memory.
b. Preprocess the data by normalizing the pixel values to be between 0 and 1.
c. Define the network architecture using a deep learning framework such as TensorFlow, Keras or PyTorch.
d. Train the network using the training data and the selected optimization algorithm (e.g., stochastic gradient descent).
e. Evaluate the trained model on the test set (Q3/q3 test.mat) and report the accuracy, training time, and inference time.

Train a model from scratch, using the data augmentation of your choice:
a. Load the training data (Q3/q3 train.mat) into memory.
b. Preprocess the data by normalizing the pixel values to be between 0 and 1.
c. Define the network architecture using a deep learning framework such as TensorFlow, Keras or PyTorch.
d. Define a data augmentation pipeline using the deep learning framework's built-in augmentation functions or custom functions.
e. Train the network using the augmented training data and the selected optimization algorithm (e.g., stochastic gradient descent).
f. Evaluate the trained model on the test set (Q3/q3 test.mat) and report the accuracy, training time, and inference time.

Compare the performance of two DCNNs:
a. Compare the accuracy, training time, and inference time of the two DCNN models trained in steps 2 and 3.
b. Consider any differences in performance due to data augmentation, network architecture, or other factors.
c. Select the model that performs better on the test set, taking into account the available computational resources.