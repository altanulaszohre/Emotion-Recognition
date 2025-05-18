# 😊 Emotion Recognition

A real-time facial **emotion recognition** project using deep learning. This model can classify human facial expressions into different emotional states such as happy, sad, angry, surprised, etc.

---

## 🔍 Project Overview

This project uses a trained CNN (Convolutional Neural Network) model to recognize emotions based on facial features. It includes:
- A training notebook
- A test interface
- Pretrained model files

---

## 🧠 Model Capabilities

The model is trained to detect the following emotions:
- 😀 Happy
- 😢 Sad
- 😠 Angry
- 😲 Surprise
- 😐 Neutral
- 😱 Fear
- 😞 Disgust

It uses a deep learning approach with TensorFlow/Keras and is suitable for real-time webcam-based detection.

---

## 🗂️ Project Structure

```
Emotion-Recognition/
│
├── EmotionRecognition/
│   ├── Emotion_Recognition.ipynb     # Model training and definition
│   ├── Test.ipynb                    # Testing the trained model
│   └── Data/
│       ├── face_model.json           # Model structure
│       ├── face_model_a.h5           # Trained weights (version 1)
│       ├── face_model_a2.h5          # Trained weights (version 2)
│       └── ld.jpg                    # Sample test image
│
├── README.md
```

---

## 🎯 Sample Outputs

Here are some example predictions made by the model:

![Sample 1](https://github.com/altanulaszohre/Emotion-Recognition/assets/111522957/8f009fa0-8f7f-4d91-9821-f997eb5fc206)

![Sample 2](https://github.com/altanulaszohre/Emotion-Recognition/assets/111522957/2234b340-9714-450f-8280-dd54d7ee7da9)

---

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Emotion-Recognition.git
   cd Emotion-Recognition/EmotionRecognition
   ```

2. **Install Requirements**:
   ```bash
   pip install tensorflow keras opencv-python matplotlib
   ```

3. **Run the Notebooks**:
   - `Emotion_Recognition.ipynb` for training (or to understand model architecture)
   - `Test.ipynb` for testing with existing images or webcam

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙌 Acknowledgments

- Thanks to the open-source community and emotion datasets
- Deep learning frameworks: TensorFlow + Keras
