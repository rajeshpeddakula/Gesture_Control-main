"# Gesture_Control-main" 
# Gesture Control Project

## Description
This project allows you to control your computer mouse using hand gestures. It uses computer vision and gesture recognition to track hand movements and translate them into mouse actions. This project was developed as part of [your purpose, e.g., a personal project, interview submission, etc.].

## Features
- **Hand Tracking**: Uses MediaPipe to detect and track hand landmarks.
- **Mouse Control**: Moves the mouse cursor based on hand position.
- **Click Gestures**: Detects specific gestures (e.g., pinching) to simulate mouse clicks.
- **Customizable**: Easily modify gesture mappings and sensitivity.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Gesture_Control-main.git
2.Navigate to the project repositary
cd Gesture_Control-main
3.Install the required dependencies:
pip install -r requirements.txt
Usage
Run the gesture control script:
python src/mouse_control.py
Follow the on-screen instructions to calibrate and use the gesture controls.

Press q to exit the program.
Dependencies
Python 3.x

OpenCV (opencv-python)

MediaPipe (mediapipe)

PyAutoGUI (pyautogui)

NumPy (numpy)

File Structure:
Gesture_Control-main/
├── README.md               # Project documentation
├── requirements.txt        # List of dependencies
├── mouse_server.py         # Flask server for gesture control
├── src/                    # Source code folder
│   └── mouse_control.py    # Main gesture control script
├── assets/                 # Folder for images, videos, etc.


