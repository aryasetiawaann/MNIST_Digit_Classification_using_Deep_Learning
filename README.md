# # MNIST Digit Classification using Deep Learning

This project implements a deep learning model to classify handwritten digits from the MNIST dataset. The dataset contains 60,000 training images and 10,000 test images, each of size 28x28 pixels, representing digits from 0 to 9.

---

## Features
- **Data Preprocessing**: Normalization of pixel values to improve training efficiency.
- **Model Architecture**:
  - Input Layer: Flattened input of size (28, 28).
  - Two Hidden Layers: Fully connected layers with ReLU activation.
  - Output Layer: Fully connected layer with 10 neurons using sigmoid activation.
- **Training**: Achieves an accuracy of 94.8% on the training set.
- **Testing**: Evaluates the model with an accuracy of 89.3% on the test set.
- **Visualization**: Includes heatmaps of confusion matrices for performance analysis.

---

## Dataset
The MNIST dataset is a benchmark dataset for handwritten digit classification:
- **Training Set**: 60,000 images.
- **Test Set**: 10,000 images.
- **Image Dimensions**: 28x28 pixels.

---

## Model Summary
- **Framework**: TensorFlow/Keras.
- **Optimizer**: Adam.
- **Loss Function**: Sparse Categorical Crossentropy.
- **Metrics**: Accuracy.
- **Epochs**: 15.

---

## Results
- **Training Accuracy**: 94.8%.
- **Testing Accuracy**: 89.3%.

**Confusion Matrix**
![Confusion Matrix]('Images/conf_mat.png')

---
