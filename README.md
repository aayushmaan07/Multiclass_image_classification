Multi-Class Image Classification with Convolutional Neural Networks
This project focuses on building a convolutional neural network (CNN) for the multi-class classification of images into six distinct categories: Buildings, Forest, Glacier, Mountain, Sea, and Street. Using TensorFlow and Keras, the model was designed to handle the complexities of diverse image data, achieving an impressive accuracy of 98%.

Project Overview
The primary goal was to develop a robust and efficient model capable of accurately classifying images into their respective categories. The dataset used contains a diverse set of images representing each of the six categories, ensuring a comprehensive training set for the model.

Technical Details
Model Architecture: The CNN model comprises multiple convolutional layers followed by max-pooling layers, designed to extract intricate features from the images. Regularization techniques, including dropout layers, were employed to prevent overfitting.
Training: The model was trained on a substantial dataset with around 10 million parameters, optimized using Adam optimizer and categorical cross-entropy loss.
Validation: Achieved 98% accuracy on the validation set, demonstrating the model's effectiveness in distinguishing between the different image categories.
Features
Libraries Used: TensorFlow, Keras, NumPy, Matplotlib
Data Augmentation: Applied techniques such as rotation, scaling, and flipping to enhance model generalization.
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
Conclusion
This project showcases a powerful application of CNNs in image classification, providing a foundation for further exploration and enhancement in computer vision tasks. The high accuracy achieved reflects the model's robustness and potential for real-world applications.
