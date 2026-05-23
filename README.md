# AUTONOMOUS-ROBOTIC-SYSTEM-FOR-PIPELINE-INSPECTION
AI-powered autonomous robotic system for real-time pipeline inspection and crack detection using CNN, Raspberry Pi, and IoT technologies. The robot enables autonomous navigation, obstacle detection, wireless monitoring, and intelligent infrastructure maintenance with edge AI processing.



## 📌 Overview

This project presents an intelligent robotic pipeline inspection system capable of detecting cracks and monitoring pipeline conditions in real time. The system combines Artificial Intelligence, Computer Vision, IoT, and Robotics to improve inspection accuracy, reduce human risk, and enable early maintenance of infrastructure.

The robot autonomously navigates through pipelines using ultrasonic sensors while a CNN-based crack detection model processes live camera input on a Raspberry Pi.

---

## 🚀 Features

- Real-time crack detection using CNN
- Autonomous robot navigation
- Obstacle detection and avoidance
- Wireless monitoring with ESP32
- Manual and auto control modes
- TensorFlow Lite edge AI deployment
- Live monitoring dashboard
- Real-time sensor data visualization

---

## 🛠️ Tech Stack

### Software
- Python
- TensorFlow Lite
- OpenCV
- NumPy
- Flask / SocketIO

### Hardware
- Raspberry Pi 4
- ESP32
- L293D Motor Driver
- HC-SR04 Ultrasonic Sensors
- USB Webcam
- DC Gear Motors
- Li-Ion Battery Pack
- LED Ring Light

---

## 📂 Dataset

The model was trained using the Surface Crack Detection Dataset containing:

- 20,000 crack images
- 20,000 non-crack images

Dataset Link:
https://www.kaggle.com/datasets/arunrk7/surface-crack-detection

---

## 🧠 CNN Model Architecture

- Input Size: 128×128×3
- 4 Convolutional Layers
- MaxPooling Layers
- Dropout Regularization
- Sigmoid Output Layer

### Model Performance

- Training Accuracy: 99.06%
- Validation Accuracy: 99.04%
- Real-time inference on Raspberry Pi 4
- Average inference speed: ~65 ms/frame

---

## ⚙️ System Workflow

1. Webcam captures real-time pipeline images
2. Raspberry Pi preprocesses image frames
3. CNN model performs crack detection
4. ESP32 transmits alerts and status updates
5. Ultrasonic sensors assist in obstacle avoidance
6. User monitors the robot through a web dashboard

---

## 📡 Applications

- Sewer pipeline inspection
- Oil and gas pipeline monitoring
- Industrial infrastructure maintenance
- Underground inspection systems
- Smart city monitoring solutions

---

## 🔮 Future Improvements

- YOLOv8-based crack localization
- NVIDIA Jetson Nano integration
- GPS-based crack location mapping
- IMU-assisted navigation
- Advanced analytics dashboard

---

## 👨‍💻 Team Members

- Devaprakash
- Haritha K Suresh
- Razaan Rasheed
- Shreya John Bosco K

---

## 🙏 Acknowledgement

We sincerely thank our project guides, faculty members, and institution for their valuable support and guidance throughout the development of this project.

---

## 📜 License

This project is developed for academic and research purposes only.
```
