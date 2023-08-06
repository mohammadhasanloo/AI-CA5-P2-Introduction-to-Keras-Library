# AI5-P2: English Alphabet Recognition with Neural Networks

This repository contains a project for recognizing the English alphabet based on their images using neural networks. The project utilizes the Keras interface to create a Forward Feed network with at least two hidden layers and a total of four layers.

## Introduction

In this project, the goal is to build a neural network that can accurately recognize the English alphabet from images. The dataset used in this project is the 'A_Z Handwritten Data' in CSV format. The neural network architecture is designed using the Keras library, and the model is trained and evaluated on the dataset.

## Phase One: Data Review and Preprocessing

The first phase involves reviewing the data and performing necessary preprocessing steps. The following steps are performed:

1. Reading CSV data using pandas: The dataset is loaded into a pandas DataFrame for further processing.

2. Separating data and labels: The data is separated from the corresponding labels and stored properly.

3. Analyzing the data: The number of data samples and available classes are calculated and displayed.

4. Visualizing class distribution: The number of images in each class is calculated, and a bar graph is plotted to visualize the class distribution.

5. Displaying one image from each class: One image is shown from each available class for visualization purposes.

6. Dividing the dataset: The dataset is split into training and testing sets with an appropriate scale.

## Phase Two: Neural Network Design

In the second phase, the neural network architecture is designed and the model is trained. The following steps are performed:

1. Data normalization: The pixel values of the images are normalized to the range [0, 1] by dividing them by 255.

2. Neural network architecture: The neural network is designed using the Keras library. The model consists of a flatten layer followed by three hidden dense layers with ReLU activation functions and an output dense layer with a softmax activation function.

3. Model compilation: The model is compiled with stochastic gradient descent (SGD) optimizer, categorical cross-entropy loss function, and accuracy, precision, recall, and F1-score metrics.

4. Model training: The model is trained on the training dataset for 10 epochs with a batch size of 32.

## Phase Three: Data Classification

The third phase involves evaluating the trained model on the test dataset. The model's performance is measured using precision, recall, and F1-score metrics for each class.

## Part 2: Epoch Number Effect

The effect of different epoch numbers on the model's performance can be observed and analyzed to determine the optimal number of epochs for training.

## Part 3: Function Loss Effect

The impact of using different loss functions on the model's performance can be investigated and compared to identify the most suitable loss function for this specific problem.

## Part 4: Regularization Effect

Regularization techniques can be applied to the model to observe their effect on generalization and prevent overfitting.

Please refer to the code files and the results for more details on each phase and part of the project.

## How to Use

1. Clone the repository to your local machine.

2. Install the required dependencies (pandas, numpy, matplotlib, tensorflow, keras, keras-metrics, sklearn).

3. Run the code files in the provided order to execute the project step by step.

4. Examine the results and analysis for each phase and part to gain insights into the performance of the neural network.

5. Modify the hyperparameters or architecture to experiment with different configurations and enhance the model's performance if desired.

Feel free to explore the code and experiment with different settings to improve the English alphabet recognition model.
