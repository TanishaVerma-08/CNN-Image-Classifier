
# 🧠 CNN Image Classifier

A Convolutional Neural Network (CNN)-based image classification project developed using Python and TensorFlow/Keras. This project demonstrates how deep learning models can be trained to accurately classify images of human facial expressions as **Happy** or **Sad**.

## 📌 Project Overview

This project aims to:
- Build and train a CNN model from scratch.
- Process and prepare image datasets of facial expressions.
- Evaluate model performance using accuracy and loss metrics.
- Make predictions on unseen facial expression images.

## 🚀 Features

- Image preprocessing with data augmentation.
- CNN architecture with convolutional, pooling, and dense layers.
- Training and validation using Keras.
- Performance visualization using Matplotlib.
- Real-time prediction functionality for new images.

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**:
  - TensorFlow / Keras
  - NumPy
  - Matplotlib
  - OS, Random, and other Python standard libraries

## 🧱 Project Structure

```
CNN Image Classifier/
│
├── CNN Image Classifier.ipynb     # Main Jupyter Notebook
├── datasets/                      # Directory for training/testing images
├── models/                        # (Optional) Saved model checkpoints
└── README.md                      # Project overview and documentation
```

## 📈 Model Architecture

The CNN model typically consists of:
- Convolutional layers for feature extraction.
- MaxPooling layers to reduce dimensionality.
- Flatten and Dense layers for classification.

## 📊 Results

- Training and validation accuracy curves are plotted to show model performance.
- The model achieved satisfactory results in classifying happy and sad facial expressions.

## 🖼️ Predictions

You can test the model by loading a new image and running the prediction code cell. The model will output whether the face in the image is **Happy** or **Sad**.

## 🧪 How to Run

1. Clone this repository or download the notebook.
2. Make sure required packages are installed:
   ```bash
   pip install tensorflow numpy matplotlib
   ```
3. Place your image dataset in the correct directory.
4. Open the `.ipynb` file and run cells sequentially.
5. Observe training results and test predictions.

## 📂 Dataset

- The dataset should contain images of happy and sad facial expressions, structured in subfolders by class:
  ```
  dataset/
  ├── train/
  │   ├── happy/
  │   └── sad/
  └── test/
      ├── happy/
      └── sad/
  ```
