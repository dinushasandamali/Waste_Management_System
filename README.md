# Waste Management System using Computer Vision 🌱

Welcome to the **Waste Classification** project, where we harness the power of **Computer Vision** to classify various types of waste, from **glass** and **plastic** to **e-waste** and **organic waste**. This project uses a **Convolutional Neural Network (CNN)** to automate the process of waste classification, contributing to the effort of a cleaner, more sustainable environment.

---

## 🧑‍💻 Project Overview

The project aims to classify images of different waste types into predefined categories. The model can identify and classify waste such as:

- **Glass** 🍾
- **Plastic** 🥤
- **Paper** 📄
- **Metal** 🥫
- **Organic Waste** 🍃
- **E-Waste** 🔋
- **Trash** 🗑️

The model leverages deep learning to enhance waste management processes, improving efficiency and reducing environmental impact.

---

## ⚙️ Dataset

The dataset used for this project is a collection of images categorized into 7 different waste types. Here's how the data is organized:

- **Glass:** Brown, green, and white glass
- **Organic:** Food waste and biodegradable items
- **Plastic:** Bottles, containers, and wrappers
- **Paper:** Newspapers, cardboard
- **Metal:** Cans, aluminum scraps
- **Trash:** Non-recyclable waste like clothes and shoes
- **E-Waste:** Batteries and electronic waste

---

## 🔬 Model Architecture

Our model is built with a **Convolutional Neural Network (CNN)**, designed to extract features from images and classify them efficiently.

### Key Model Components:
- **Conv2D + ReLU Activation:** For feature extraction.
- **MaxPooling:** To reduce the dimensionality of the image data.
- **Dense Layers:** Fully connected layers that help the model classify the images.
- **Dropout:** To reduce the risk of overfitting.

### Model Details:
- **Input:** 224x224 images with 3 RGB color channels.
- **Output:** Multi-class classification using Softmax activation.
- **Training:** Adam optimizer, binary crossentropy loss, batch size of 256, and 50 epochs.

---

## 📈 Results

The model has shown promising results in classifying waste images accurately. With balanced classes and data augmentation, the training process was efficient, and the model achieved an excellent level of accuracy.

