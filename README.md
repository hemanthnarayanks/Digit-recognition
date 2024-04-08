
# Digit Recognition Project

This is a Digit Recognition project, which takes the inputs as array of pixel which are hand written digits and recognizes them.

size:
28*28 pixels

Libraries used:
Numpy
Tensorflow
Open CV
Matplotlib
Pandas

The dataset(MNIST) is loaded from keras datasets and on which the recognition is performed.
The train and test data are 80% and 20% respectively.

The data is normalized to obtain better accuracy.
(//255) or (can use normalize from keras.utils)

Built a Neural Network model,with a 3 Dense hidden layers of 128 units each and "RELU"(Rectified Linear Unit) Activation function, the output layer is of 10 units from 0-9, producing the output using "SoftMax" activation function.

The optimizer used is "Adam" and the loss/cost function used is "Sparse_categorical_crossentropy" since the output data in train dataset or test dataset is not onehotencoded.

Using the above model the accuracy obtained is 0.97 with a loss of 0.11

Later, I created a document with hand written digits data using paint.
Using the OpenCV module to read the image which is in png format of 28*28 size and performed recognition of those hand written digits using the same model.









## Installation

Modules are to be preinstalled before importing them.

Install CV2

Since CV2 or CV requires OpenCV module.
```bash
pip install opencv-python 
import cv2 
```
For remaining libraries
```bash
pip install library_name
```    