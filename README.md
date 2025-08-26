# Hand Gesture Controlled Keyboard Actions

This project uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to detect hand gestures using a webcam and perform specific keyboard actions based on the number of fingers detected.

## 📌 Features
- Detects hand and finger landmarks in real-time using MediaPipe.
- Counts the number of raised fingers.
- Performs keyboard actions based on finger count:
  - **1 Finger** → Presses "Right Arrow"
  - **2 Fingers** → Presses "Left Arrow"
  - **3 Fingers** → Presses "Up Arrow"
  - **4 Fingers** → Presses "Down Arrow"
  - **5 Fingers** → Presses "Space"

## 🛠️ Requirements
Install the following Python libraries before running the project:

```bash
pip install opencv-python mediapipe pyautogui
