# ✍️ Handwritten Digit Classification using Convolutional Neural Networks (CNN)

This project provides a complete solution notebook for the classic task of classifying handwritten digits using a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras. It uses the widely known **MNIST** dataset, which consists of 28x28 grayscale images of the digits 0 through 9.

---

## 🎯 Project Goals

The objective of this notebook is to implement and evaluate a high-accuracy CNN model for image classification. It specifically demonstrates:

1.  **Data Loading & Visualization:** Loading the MNIST dataset and displaying sample images to understand the data.
2.  **Preprocessing:** Normalizing pixel data and handling the image input shape for CNN layers.
3.  **Model Architecture:** Defining a simple yet effective CNN architecture using 2D convolutional and pooling layers.
4.  **Training & Evaluation:** Training the model and assessing its performance (accuracy and loss) on the test set.

## ⚙️ Technology Stack and Dependencies

The project is built on the core components of the Python data science and deep learning stack.

| Library | Role |
| :--- | :--- |
| **`tensorflow / keras`** | Core framework for building and training the CNN model. |
| **`layers.Conv2D, layers.MaxPooling2D`** | Used to define the convolutional architecture for feature extraction. |
| **`matplotlib.pyplot`** | Used for displaying sample images from the dataset. |
| **`numpy`** | Used for efficient numerical data handling. |

### Installation

```bash
pip install tensorflow matplotlib numpy
