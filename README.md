# 👤 Gender and Age Detection using OpenCV & Deep Learning

A Python-based computer vision project that detects a person's **gender** and **age group** from an image or webcam feed using OpenCV's Deep Neural Network (DNN) module and pretrained Caffe models.

---

## 🎯 Objective

To build a real-time gender and age detection system that predicts:

- **Gender:** Male / Female
- **Age Groups:**
  - (0–2)
  - (4–6)
  - (8–12)
  - (15–20)
  - (25–32)
  - (38–43)
  - (48–53)
  - (60–100)

---

## 🚀 Features

- Detects faces using OpenCV DNN.
- Predicts gender and age from a single image.
- Supports webcam-based real-time detection.
- Uses pretrained deep learning models.
- Fast and easy to use.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- Deep Learning (Caffe Models)
- DNN Module

---

## 📂 Project Structure

```
Gender-and-Age-Detection/
│
├── detect.py
├── age_deploy.prototxt
├── age_net.caffemodel
├── gender_deploy.prototxt
├── gender_net.caffemodel
├── opencv_face_detector.pbtxt
├── opencv_face_detector_uint8.pb
├── Example/
├── Output/
└── README.md
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/sailinishavempali/Gender-and-Age-Detection.git
cd Gender-and-Age-Detection
```

Install dependencies:

```bash
pip install opencv-python
```

---

## ▶️ Usage

### Detect age and gender from an image

```bash
python detect.py --image girl1.jpg
```

Replace `girl1.jpg` with your own image file.

### Detect age and gender using webcam

```bash
python detect.py
```

Press **Ctrl + C** to stop the webcam.

---

## 📷 Sample Output

<p align="center">
    <img src="Example/Detecting age and gender girl1.png" width="500">
</p>

---

## 📊 Example Prediction

```
Image : girl1.jpg

Gender : Female

Age : 25-32 Years
```

---

## 📁 Dataset

The pretrained models used in this project were trained on the **Adience Dataset**, which contains over **26,000** face images collected under real-world conditions including variations in pose, lighting, and facial expressions.

---

## 💡 My Contribution

- Configured and executed the project.
- Tested the pretrained deep learning models.
- Verified image and webcam inference.
- Organized the project structure.
- Improved project documentation.
- Published the project on GitHub for learning and portfolio purposes.

---

## 🙏 Acknowledgement

This project uses publicly available pretrained Caffe models trained on the Adience Dataset. Thanks to the open-source community for making these resources available for learning and research.

---

## 👩‍💻 Author

**Sai Linisha Vempali**

GitHub: https://github.com/sailinishavempali

⭐ If you found this project helpful, consider giving it a star!
