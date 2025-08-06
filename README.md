# 🚦 Traffic Sign Recognition with CNN

This project uses deep learning to recognize and classify German traffic signs using the GTSRB dataset. It demonstrates preprocessing techniques, model training with CNN, and performance evaluation.

## 📂 Dataset

- **Source**: [GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- Includes annotated images of 43 traffic sign classes.
- Preprocessing includes:
  - Image resizing (typically to 32x32 or 64x64)
  - Normalization
  - Data augmentation (optional)

## 🧠 Model

- Built using **Keras** and **TensorFlow**
- Uses a **Convolutional Neural Network (CNN)** architecture
- Key layers: `Conv2D`, `MaxPooling`, `Flatten`, `Dense`, and `Dropout`
- Optimizer: `Adam`
- Loss function: `categorical_crossentropy`

## 📊 Evaluation

- Accuracy and loss curves plotted using `matplotlib`
- Confusion matrix to visualize classification performance
- Optionally supports real image predictions

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/traffic-sign-recognition.git
   cd traffic-sign-recognition
