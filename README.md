# Facial Emotion Recognition 🎭  
A deep-learning based project that detects human emotions (Happy, Sad, Angry, Surprise, Neutral, etc.) from facial images using Convolutional Neural Networks (CNN).

---

## 🚀 Project Overview
This project builds a **Facial Emotion Recognition (FER)** system trained on a labeled dataset of human facial expressions.  
The model can classify images into multiple emotion categories such as:

- 😊 Happy  
- 😞 Sad  
- 😡 Angry  
- 😲 Surprise  
- 😐 Neutral  
- 😁 Fear  
- 😖 Disgust  

The project is built using **Python**, **TensorFlow/Keras**, and **OpenCV**.

---

## 🧠 CNN Model Architecture
The model uses a custom CNN with the following layers:

- Convolution Layers  
- MaxPooling  
- Dropout  
- Dense Fully Connected Layers  
- Softmax for multi-class classification  

Loss function: **categorical_crossentropy**  
Optimizer: **Adam**  
Accuracy achieved: *depends on training* (usually 60–75%)
