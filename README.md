# Multiclass_image_classification
This repository contains a project on building a Convolutional Neural Network (CNN) model for multi-class classification of images into six categories: Buildings, Forest, Glacier, Mountain, Sea, and Street. The model is implemented using TensorFlow and Keras and achieves an impressive accuracy of 98%.

###Model Architecture
The CNN architecture used in this project is as follows:

Input Layer: Images resized to (150, 150, 3)
Conv2D Layers: Three convolutional layers with increasing filter sizes (32, 64, 128) and kernel size (3, 3), using ReLU activation and 'same' padding
MaxPooling2D Layers: After each Conv2D layer to reduce spatial dimensions
Dropout Layers: Dropout rate of 0.5 and 0.2 added after flattening to prevent overfitting
Flatten Layer: To convert 2D matrix data to a 1D vector
Dense Layers: One dense layer with (1024,256,128,64) units and ReLU activation
Output Layer: Dense layer with 6 units and softmax activation for multi-class classification

###Training Details
Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Metrics: Accuracy
Epochs: 30
Batch Size: 32
Data Augmentation: Applied to prevent overfitting
Dataset: Image dataset divided into training, validation, and test sets

###Performance
Training Loss: 1.5%
Validation Loss: 6.8%
Accuracy: 98%
