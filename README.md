# Plant-Disease-Prediction-Project
## Overview:
This project aims to predict plant diseases using Convolutional Neural Networks (CNNs) based on images of plant leaves. The dataset used is the PlantVillage dataset, obtained from Kaggle, containing images of various plant diseases and healthy plant samples.
## Key Components:
**Data Collection:**

Kaggle API is utilized to download the PlantVillage dataset.
The dataset is organized into categories representing different plant diseases and a healthy category.

**Data Preprocessing:**

Images are loaded, and their shapes are examined.
Image resizing is performed to a standard size.
Image Data Generators are set up for efficient loading and augmentation.

**Train-Test Split:**

The dataset is split into training and validation sets using Keras' flow_from_directory method.

**Convolutional Neural Network (CNN):**

A CNN model is defined with convolutional and pooling layers.
The model is compiled using the Adam optimizer and categorical crossentropy loss.
Training is conducted on the training set, and the model is evaluated on the validation set.

**Model Evaluation:**

The trained model's accuracy and loss are visualized using matplotlib.
The model is evaluated on the validation set, and accuracy is printed.

**Image Prediction Function:**

A function is defined to predict the class of a given image using the trained model.
The function includes image loading, preprocessing, and predicting the class.

**Usage Example:**

An example is provided, demonstrating how to use the model for predicting the class of an image.

**Results and Output:**

The model's validation accuracy is 87.20.

**Class Indices Mapping:**

A mapping from class indices to class names is saved as a JSON file for reference.
