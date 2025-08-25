HAND GESTURE MOUSE CONTROL
````markdown
 🖐️ Hand Gesture Mouse Control

Control your computer’s mouse **using just your hand gestures** captured via webcam!  
This project uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to track your hand in real-time and translate movements into mouse actions such as moving and clicking.

---

 ✨ Features
- 🎥 Real-time hand tracking with **MediaPipe Hands**
- 🖱️ Control mouse cursor using your **index finger**
- 👆 Perform left-click when **thumb & index finger come close**
- 🔄 Smooth and responsive tracking with OpenCV
- 💻 Works on any system with a webcam

---
 🛠️ Tech Stack
- [Python 3.x](https://www.python.org/)
- [OpenCV](https://opencv.org/) – for video capture & image processing
- [MediaPipe](https://developers.google.com/mediapipe) – for hand landmark detection
- [PyAutoGUI](https://pyautogui.readthedocs.io/) – for mouse control

---

📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/MGKTHECREATOR/Hand-Gesture-Mouse-Control.git
   cd Hand-Gesture-Mouse-Control
````

2. Install dependencies:

   bash
   pip install opencv-python mediapipe pyautogui
   

▶️ Usage

Run the Python script:

bash
python mouse.py


* Move your **index finger** → moves the mouse cursor
* Bring **thumb close to index finger** → performs a left click
* Press **ESC** → exit program


📂 Project Structure

📦 Hand-Gesture-Mouse-Control
 ┣ 📜 mouse.py        # Main program
 ┣ 📜 README.md       # Project documentation
 ┗ 📜 requirements.txt (optional)
🎯 Demo

👉 *(You can add a GIF/screenshot here later for better presentation)*



🚀 Future Improvements

* Add **right-click** & **double-click** gestures
* Enable **scrolling with hand movements**
* Improve cursor **smoothness & stability**


🧑‍💻 Author
**MGK The Creator**
🔗 [GitHub](https://github.com/MGKTHECREATOR)
