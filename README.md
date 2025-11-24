# Snake Game – Hand Gesture Controlled 🐍✋

Play the classic Snake Game using **hand gestures**! Control the snake in real-time using your webcam with OpenCV, MediaPipe, and Pygame.  

Check it out on GitHub: [Snake Game Hand Gesture](https://github.com/suhanigupta23/Snake-Game-Hand-Gesture/upload)

---

## 🎮 Features

- Real-time hand gesture recognition.
- Control the snake without a keyboard.
- Smooth gameplay with OpenCV and Pygame.
- Fun and interactive classic Snake experience.

---

## ⚙️ Requirements

- Python 3.8 or higher
- Webcam
- pip (Python package manager)

---

<img width="1252" height="609" alt="Screenshot 2025-11-24 at 11 41 11 PM" src="https://github.com/user-attachments/assets/465d631f-93a4-4879-9ba4-4317c01ee145" />

## 🛠️ Quick Setup & Run

Open a terminal and follow these commands **after cloning the repository**:

```bash
# Navigate into your project folder
cd Snake-Game-Hand-Gesture

# Create Python virtual environment
python3 -m venv gesture-env

# Activate virtual environment
# Linux / MacOS
source gesture-env/bin/activate

# Windows
gesture-env\Scripts\activate

# Install dependencies
pip install opencv-python
pip install mediapipe
pip install numpy
pip install pygame

# Run the game
python3 opencv_control.py

