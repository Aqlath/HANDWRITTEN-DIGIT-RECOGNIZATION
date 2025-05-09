# HANDWRITTEN-DIGIT-RECOGNIZATION
# 🧠 Handwritten Digit Recognition using CNN and Streamlit

This project demonstrates a deep learning-based handwritten digit recognition system built using **TensorFlow**, **Keras**, and **Streamlit**. The model is trained on the **Kaggle MNIST CSV dataset** and deployed as a web application where users can upload an image and receive instant predictions.

---

## 📌 Project Overview

- **Goal:** Classify handwritten digits (0–9) using a Convolutional Neural Network (CNN).
- **Input:** 28x28 grayscale PNG image of a handwritten digit.
- **Output:** Predicted digit shown in a user-friendly web app.
- **Interface:** Built using **Streamlit** for easy deployment and interaction.

---

## 📁 Folder Structure
├── app.py ← Streamlit application <br>
├── digit_model.keras ← Trained CNN model
├── requirements.txt ← List of Python dependencies
├── mnist_train.csv ← (Optional) Kaggle MNIST training data
├── mnist_test.csv ← (Optional) Kaggle MNIST test data
└── README.md ← Project documentation (this file)
