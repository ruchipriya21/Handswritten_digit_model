# Handwritten Digit Recognition

This project aims to develop a model that can recognize handwritten digits using machine learning techniques. The model will be trained on a dataset of labeled images of handwritten digits (0-9) to learn the patterns and features associated with each digit.

## Dataset

The dataset used for training and evaluation is the MNIST dataset, which is a widely-used benchmark dataset for handwritten digit recognition. It consists of 60,000 labeled training images and 10,000 labeled test images, each of size 28x28 pixels.

## Model Architecture

The chosen model architecture for this task is a simple neural network. The architecture consists of three neural layers.

The architecture can be summarized as follows:

1. Neura Layer 1: 100 units, ReLU activation
2. Neural Layer 2: 100 units, ReLU activation
3. Output Layer: 10 units (one for each digit), softmax activation

## Training

The model is trained using the training set of the MNIST dataset. The training process involves feeding the images into the model, computing the prediction, and comparing it with the actual label. The model parameters are optimized using Adam optimizer

The training hyperparameters used in this project are as follows:
- Number of Epochs: 20

## Evaluation

The trained model is evaluated using the test set of the MNIST dataset. The evaluation process involves feeding the test images into the model and comparing the predicted labels with the actual labels. The evaluation metrics used for this project are accuracy and confusion matrix.

## Usage

To use the trained model for recognizing handwritten digits, follow these steps:

1. Preprocess the input image:
   - Resize the image to 28x28 pixels.
   - Normalize the pixel values to the range [0, 1].
2. Load the trained model weights.
3. Feed the preprocessed image into the model.
4. Obtain the predicted digit label from the output layer of the model.

## Conclusion

This project demonstrates the use of a simple neural network for handwritten digit recognition. The model achieved an accuracy of 97.6% on the test set of the MNIST dataset, showcasing its effectiveness in recognizing handwritten digits. The trained model can be utilized in various applications, such as digit recognition in postal services, automated form processing, and more.

## 6. Support and Contact
If you have any questions, issues, or feedback regarding the project, please feel free to reach out. You can contact me through the following channel:
- Email: priya21ruchi@gmail.com
