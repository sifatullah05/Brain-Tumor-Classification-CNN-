# Brain Tumor Classification

## 📌 Project Overview
This project aims to classify brain tumors into different categories using deep learning. The dataset consists of MRI images, and the models are trained to accurately detect and classify tumors.

---

## 🧠 Models Used

### 1️⃣ Custom CNN Model
- Built a custom Convolutional Neural Network from scratch.
- Architecture includes:
  - Convolutional layers
  - MaxPooling layers
  - Batch Normalization
  - Dropout for regularization
- Designed to learn features directly from MRI images.

---

### 2️⃣ MobileNetV2 (Transfer Learning)
- Utilized MobileNetV2 pre-trained on ImageNet.
- Fine-tuned the last 20–30 layers for brain tumor classification.
- Added:
  - Global Average Pooling
  - Dense layers
  - Dropout layer for better generalization
- Benefits:
  - Faster training
  - Good accuracy on small datasets

---

### 3️⃣ ResNet50 (Transfer Learning)
- Used ResNet50 with pre-trained ImageNet weights.
- Added Global Average Pooling and Dense layers.
- Fine-tuned last few layers to adapt to brain tumor classification.
- Achieved high accuracy using feature extraction from deep residual networks.

---

### 4️⃣ EfficientNetB0 (Transfer Learning)
- Used EfficientNetB0 pre-trained on ImageNet.
- Added custom Dense layers and Dropout for classification.
- Fine-tuned top layers for better performance on MRI images.
- Advantages:
  - High efficiency with fewer parameters
  - Good balance between accuracy and computation

---

## 🗂 Dataset
- MRI images of brain tumors.
- Divided into training and testing sets.
- Images are preprocessed using data augmentation:
  - Rotation
  - Zoom
  - Horizontal & vertical flips
  - Width & height shifts
  - Shear transformation
  - Rescaling (1./255)

---

.txt
