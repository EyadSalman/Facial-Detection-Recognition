# 🧠 Facial Detection & Emotion Recognition

A computer vision project that detects faces and recognizes human emotions (like Happy, Angry, Surprise) using deep learning trained on a Kaggle dataset.

---

## 📸 Features
- Real-time face detection using OpenCV Haar Cascades
- Emotion recognition (Happy, Angry, Surprise, etc.)
- Train your own model easily on the provided dataset
- Works on images, webcam streams, and video files
- Lightweight and fast

---

## 🛠️ Tech Stack
- **Python 3.8+**
- **OpenCV** (for face detection)
- **TensorFlow / Keras** (for CNN-based emotion recognition)
- **NumPy** (for array operations)
- **Matplotlib** *(optional, for visualization)*

---

## 📂 Project Structure
```
├── dataset/
│   ├── train/
│   │   ├── angry/
│   │   ├── happy/
│   │   ├── surprise/
│   │   └── ... (other emotions)
│   ├── test/
│       ├── angry/
│       ├── happy/
│       ├── surprise/
│       └── ... (other emotions)
├── models/
│   └── emotion_model.h5    # Trained CNN model
├── requirements.txt
└── README.md
```
