# 🤖 AI Smart Vision Pro Max

An advanced multi-model AI vision system that performs real-time image analysis using deep learning models.

---

## 🚀 Features

* 📦 Object Detection using YOLOv8s
* 🖼️ Scene Classification using EfficientNetB0
* 👤 Face & Gender Detection using DeepFace
* 📷 Real-time webcam capture (Google Colab)
* 🏷️ Smart category grouping (Human, Vehicle, Animal, etc.)
* 📊 Detailed AI-generated analysis report
* 🎯 Bounding box visualization on detected objects and faces

---

## 🧠 Models Used

* YOLOv8s → Object Detection
* EfficientNetB0 → Image Classification
* DeepFace → Face & Gender Detection

---

## ⚙️ Installation

Run this command:

pip install ultralytics deepface opencv-python-headless pillow matplotlib tensorflow

OR use requirements file:

pip install -r requirements.txt

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Run all cells
3. Webcam will open
4. Capture image
5. AI will analyze and display results

---

## 📊 Sample Output

OBJECT DETECTION:

* person: 2
* laptop: 1

SMART CATEGORIES:

* Human
* Electronics

SCENE CLASSIFICATION:

* office: 85%
* desktop computer: 10%

FACE DETECTION:

* Face 1: Male (92%)

---

## ⚠️ Notes

* Gender detection is for demo purposes only
* Accuracy depends on lighting and image quality
* Models download automatically on first run

---

## 💡 Future Improvements

* Age detection
* Emotion detection
* Real-time video streaming
* Web app deployment (Streamlit / Flask)

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* YOLOv8 (Ultralytics)
* OpenCV
* DeepFace
* Google Colab

---

## 👩‍💻 Author

Prachi Chandel
BCA Graduate | Aspiring Data Scientist

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
