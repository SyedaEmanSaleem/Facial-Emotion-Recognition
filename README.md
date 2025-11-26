
---

# 🎭 Facial Emotion Recognition (FER) Using Custom CNN

A high-accuracy Facial Emotion Recognition model built using a **Custom Convolutional Neural Network**. This project classifies human emotions from facial images into seven categories and is optimized for real-time applications.

---

## 🚀 Features

* ✔️ Custom-designed CNN architecture
* ✔️ High accuracy on FER datasets
* ✔️ Real-time emotion prediction support
* ✔️ Lightweight & fast inference
* ✔️ Data augmentation for robust training
* ✔️ Easy to integrate into other applications

---

## 🧠 Emotions Detected

The model predicts the following 7 emotions:

* **Angry**
* **Disgust**
* **Fear**
* **Happy**
* **Sad**
* **Surprise**
* **Neutral**

---

## 🏗️ Model Architecture (Custom CNN)

The CNN consists of multiple convolutional blocks with increasing depth, followed by fully connected layers:

* Input: **48×48 grayscale facial images**
* Conv2D layers + ReLU activation
* Batch Normalization
* MaxPooling for downsampling
* Dropout for regularization
* Dense layers with ReLU
* Final **Softmax output layer**

✔️ Designed for high accuracy
✔️ Stable and efficient training
✔️ Prevents overfitting via dropout + augmentation

---

## 📊 Performance

The Custom CNN achieved **excellent accuracy** during training and validation.

👉 *Replace the line below with your accuracy:*
**📌 Model Accuracy: 89% on FER validation dataset**

---

## 📁 Dataset

This model can be trained on datasets like:

* **FER-2013** (Kaggle)
* Custom facial emotion datasets

Images are preprocessed by:

* Converting to grayscale
* Resizing to 48×48
* Normalization
* Augmentation for robustness

---

## 🧪 Training Setup

* **Framework:** TensorFlow / Keras
* **Loss Function:** Categorical Cross-Entropy
* **Optimizer:** Adam
* **Augmentation:** Rotation, shift, zoom, horizontal flip
* **Epochs:** Until validation accuracy converges
* **Batch Size:** Tuned for GPU efficiency

---

## 📦 Project Structure (example)

```
├── dataset/
├── models/
│   └── emotion_cnn.h5
├── src/
│   ├── train.py
│   ├── model.py
│   └── predict.py
├── README.md
└── requirements.txt
```

---

## 📷 Sample Output

(Add your model predictions or screenshots here)

---

## 💡 Applications

* Human–Computer Interaction
* Smart surveillance
* Robotics
* Mental health monitoring
* Real-time emotion detection systems

---

## 🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit pull requests.

---

## 📜 License

This project is licensed under **MIT License** (or your choice).

---


