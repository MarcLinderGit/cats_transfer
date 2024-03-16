# Cat-Dog Image Classifier with Transfer Learning

In this notebook, I'll build a powerful image classifier using transfer learning with pre-trained neural networks. The main goal is to leverage the knowledge learned by networks trained on the extensive ImageNet dataset to achieve impressive accuracy in distinguishing between cat and dog images.

## Project Overview

### 1. Loading Essentials
   - Importing crucial PyTorch libraries for the project.
   - Defining the path to my cat and dog image dataset.
   - Setting up data transformations for effective training and testing.

### 2. Utilizing Pre-trained Models
   - Exploring the capabilities of `torchvision.models` to access pre-trained networks.
   - Loading a pre-trained ResNet50 model to serve as the foundation.

### 3. Customizing and Training the Classifier
   - Modifying the pre-trained ResNet50 model to suit the specific cat and dog classification task.
   - Freezing parameters to retain the pre-trained knowledge.
   - Setting up the loss function, optimizer, and initiating the training process.

### 4. Training the Classifier (Output Layer)
   - Specifying the number of epochs and defining key training parameters.
   - Iterating through epochs to train the network.
   - Evaluating the model's performance on the test set.

### 5. Plotting Train & Test Loss
   - Visualizing the training and validation loss over epochs for insights.

### 6. Inference
   - Testing the trained network on a subset of the test data to ensure robust performance.

### 7. Visualization of Predictions
   - Developing a function to visually assess model predictions.
   - Displaying predictions for five handpicked images from the test dataset.