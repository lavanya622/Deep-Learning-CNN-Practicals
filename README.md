# 🧠 Convolutional Neural Network (CNN) Practicals

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red?logo=keras)
![Status](https://img.shields.io/badge/Status-Learning%20Projects-success)

## 📌 Overview

This repository contains hands-on implementations of **Convolutional Neural Networks (CNNs)** using Python, TensorFlow, and Keras. These projects demonstrate how deep learning models process images, learn visual patterns, and perform image classification.

The repository includes two practical projects covering handwritten digit recognition and animal image classification.

## 🎯 Objectives

- Understand the fundamentals of CNN architecture.
- Learn convolution, activation, and pooling operations.
- Apply image preprocessing and normalization.
- Implement image classification models using TensorFlow and Keras.
- Train models and evaluate their performance.
- Visualize training and validation accuracy and loss.
- Make predictions on unseen images.

## 📂 Projects Included

### 1. MNIST Handwritten Digit Classification

**Objective:** Classify handwritten digits into one of ten classes, from 0 to 9.

**Dataset:** MNIST handwritten digit dataset.

**Key Concepts:**
- Image loading and preprocessing
- Pixel normalization
- `Conv2D` convolution layers
- ReLU activation
- `MaxPooling2D`
- Flatten and Dense layers
- Dropout regularization
- Softmax output for multiclass classification
- Model evaluation and digit prediction

**Expected Output:** A predicted digit label for each input image, along with model performance metrics and training graphs.

### 2. Cat and Dog Image Classification

**Objective:** Build a CNN model that classifies images into two categories: cats and dogs.

**Dataset:** [Cats and Dogs Filtered Dataset on Kaggle](https://www.kaggle.com/datasets/birajsth/cats-and-dogs-filtered)

**Key Concepts:**
- Loading image datasets from directories
- Image resizing to 150 × 150 pixels
- Pixel normalization using rescaling
- Data augmentation using rotation, shifting, zooming, and horizontal flipping
- Binary image classification
- Convolution and max-pooling layers
- Dropout and batch normalization
- Model training and validation
- Accuracy and loss visualization
- Prediction on a new image

**Model Architecture:**

`Input Image → Conv2D → MaxPooling2D → Dropout → BatchNormalization → Conv2D → MaxPooling2D → Dropout → BatchNormalization → Flatten → Dense → Dropout → BatchNormalization → Sigmoid Output`

**Expected Output:** A prediction identifying the input image as either **Cat** or **Dog**.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow
- **Neural Network API:** Keras
- **Numerical Computing:** NumPy
- **Data Visualization:** Matplotlib
- **Image Processing:** OpenCV (for the custom-image prediction step)
- **Dataset Source:** MNIST and Kaggle

## 🧠 What Is a CNN?

A Convolutional Neural Network is a deep learning architecture commonly used for image-related tasks. It automatically learns visual features such as edges, shapes, textures, and more complex patterns.

### Main CNN Components

| Component | Purpose |
|---|---|
| Convolution | Extracts features from images |
| ReLU | Introduces non-linearity |
| Max Pooling | Reduces feature-map dimensions |
| Flatten | Converts feature maps into a one-dimensional vector |
| Dense | Learns relationships between extracted features |
| Dropout | Helps reduce overfitting |
| Batch Normalization | Helps stabilize and accelerate training |
| Sigmoid | Produces an output for binary classification |
| Softmax | Produces class probabilities for multiclass classification |

## ⚙️ Installation

Install the required libraries using pip:

```bash
pip install tensorflow numpy matplotlib opencv-python kagglehub
```

For notebook execution, you can use **Google Colab**, Jupyter Notebook, or VS Code with a configured Python environment.

## ▶️ How to Run

1. Clone or download this repository.
2. Open the required `.ipynb` notebook.
3. Install the dependencies.
4. Download or load the appropriate dataset.
5. Run the notebook cells in order.
6. Review the model summary and training graphs.
7. Test the trained model using sample or new images.

**Note:** The Cat and Dog notebook currently uses Google Colab paths such as `/content/Dataset` and `/content/cat.jpg`. Update these paths if you run the notebook locally in VS Code or Jupyter.

The Cat and Dog project also requires access to the Kaggle dataset download process configured in the notebook.

## 📊 Evaluation

The practicals explore model evaluation through:

- Training accuracy
- Validation accuracy
- Training loss
- Validation loss
- Predictions on test or new images

Actual performance depends on dataset quality, preprocessing, model configuration, and training settings. Refer to the executed notebook outputs for the measured results.

## 📚 Learning Outcomes

By completing these projects, I practiced:

- Building CNN architectures using Keras.
- Understanding image preprocessing and augmentation.
- Working with binary and multiclass image classification.
- Training and validating deep learning models.
- Visualizing learning curves.
- Applying a trained model to image prediction tasks.

## 🚀 Future Improvements

- Experiment with different CNN architectures and hyperparameters.
- Improve generalization through additional data augmentation.
- Add a confusion matrix and classification report.
- Save and reload trained models for inference.
- Explore transfer learning using pretrained models such as MobileNetV2.
- Build a simple web interface for image classification.



⭐ If you find these practicals useful, feel free to explore the notebooks and learn along with me.

**Learning Journey:** Machine Learning → Deep Learning → CNN → Image Classification
