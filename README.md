# 🖐️ OpenCV Hand Gesture Control System

## 📌 Overview
This project is a computer vision-based system built using Python and OpenCV to detect and recognize hand gestures in real time. The detected gestures are used to control actions through serial communication.

---

## 🚀 Features
- Real-time hand gesture detection using OpenCV  
- Finger state recognition (0/1 for each finger)  
- Serial communication between Python and external device  
- Smooth and responsive gesture tracking  
- Simple and efficient implementation  

---

## 🛠️ Technologies Used
- Python  
- OpenCV  
- Serial Communication (PySerial)  
- Computer Vision Techniques  

---

## ⚙️ Working Principle
- Camera captures live video feed  
- OpenCV processes frames to detect hand and fingers  
- Each finger state is converted into binary values (0 or 1)  
- Data is sent via serial communication to control outputs  

---

## 💡 Example Logic (Output Control)
```cpp
int ledPins[] = {8, 9, 10, 11, 12};  // Finger-controlled outputs
▶️ How to Run
Clone the repository
git clone https://github.com/yourusername/opencv-gesture-control.git
Install dependencies
pip install opencv-python pyserial
Run the Python script
python main.py

👨‍💻 Author

Roopas Kumar
