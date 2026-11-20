# 👟 Nike vs Adidas Image Classification Using CNN

## 📌 Project Overview

This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify images into two categories: **Nike** and **Adidas**.

The model takes an input image, processes it using convolutional and pooling layers, and predicts whether the image belongs to Nike or Adidas.

## 🎯 Project Objectives

- Classify Nike and Adidas images automatically.
- Understand the working process of CNN.
- Perform image preprocessing and resizing.
- Build and train a deep learning model.
- Predict image categories using Softmax activation.

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Pillow (PIL)
- TensorFlow / Keras
- Convolutional Neural Network (CNN)
- Google Colab / Jupyter Notebook

## 🧠 Model Architecture

The CNN model consists of the following layers:

1. Input Layer – 120 × 120 grayscale images.
2. Convolutional Layer – 16 filters.
3. Max Pooling Layer.
4. Convolutional Layer – 32 filters.
5. Max Pooling Layer.
6. Convolutional Layer – 64 filters.
7. Max Pooling Layer.
8. Flatten Layer.
9. Dense Layer – 64 neurons.
10. Dropout Layer – 0.2.
11. Output Layer – 2 neurons with Softmax activation.

## ⚙️ Data Preprocessing

- Load images from training folders.
- Convert images into grayscale.
- Resize images to 120 × 120 pixels.
- Convert images into NumPy arrays.
- Normalize pixel values between 0 and 1.
- Assign labels:
  - Nike: [1, 0]
  - Adidas: [0, 1]

## 🚀 Model Training

The model is compiled using:

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Evaluation Metric: Accuracy
- Training Epochs: 10

## 📂 Project Structure

```text
Deep-Learning-Project/
│
├── CNN_project(1).ipynb
└── README.md
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open Google Colab or Jupyter Notebook.
3. Upload the notebook.
4. Prepare the Nike and Adidas image datasets.
5. Configure the training and testing dataset paths.
6. Run all notebook cells.
7. Train the CNN model and observe the results.

## 📈 Expected Output

The trained CNN model predicts whether an input image belongs to:

- Nike
- Adidas

## 📚 Learning Outcomes

- Understanding CNN architecture.
- Image preprocessing techniques.
- Working with Keras and NumPy.
- Understanding convolution and pooling operations.
- Training a deep learning image classification model.

Deep Learning Project – Nike vs Adidas Image Classification.
