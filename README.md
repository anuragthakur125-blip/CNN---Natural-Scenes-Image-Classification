# CNN - Natural Scenes Image Classification

This project uses a Convolutional Neural Network (CNN) to classify natural scene images into three categories: **Buildings, Forest, and Sea**.

## Project Overview

The project demonstrates an end-to-end image classification workflow using **Python, TensorFlow, and Keras**. Images are preprocessed and augmented before being passed to a CNN model for classification.

## Classes

- Buildings
- Forest
- Sea

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib

## Project Workflow

1. Load and explore the image dataset
2. Visualize sample images from each category
3. Preprocess images using rescaling
4. Apply image augmentation such as:
   - Rotation
   - Width and height shifting
   - Shearing
   - Zooming
   - Horizontal flipping
5. Create training and validation image generators
6. Build a CNN model using:
   - Convolutional layers
   - Max Pooling layers
   - Flatten layer
   - Dense layers
   - Dropout
7. Train the model using the Adam optimizer
8. Use Early Stopping to reduce overfitting
9. Evaluate training and validation performance using loss and accuracy curves

## Model Architecture

The CNN consists of:

- 3 Convolutional layers
- 3 Max Pooling layers
- Flatten layer
- Dense layer with 128 neurons
- Dropout layer
- Softmax output layer with 3 classes

## Results

The notebook reports training and validation accuracy above **90%**, indicating that the model achieved good classification performance on the available dataset.

## Conclusion

This project demonstrates how CNNs can be used for automated image classification and how image augmentation and model evaluation can improve the overall machine learning workflow.
