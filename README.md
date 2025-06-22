🎛️ Volume Control using Hand Gesture
Control your system volume with just a wave of your hand! This project uses Python, OpenCV, and MediaPipe to create a real-time, gesture-based volume control system using a webcam.

🧠 Features
🖐️ Detects hand gestures using MediaPipe Hands

🎚️ Controls system volume based on distance between thumb and index finger

💻 Real-time video feed with gesture overlay

⚙️ Works on Windows using PyCaw for volume control

🛠️ Tech Stack
Python

OpenCV – for camera access and frame rendering

MediaPipe – hand tracking and landmark detection

PyCaw – control Windows system audio

📦 Installation
bash
Copy
Edit
# Clone the repo
git clone https://github.com/rohithap0819/Volume-Control-using-Hand-Gesture.git
cd Volume-Control-using-Hand-Gesture

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt
🧪 Usage
bash
Copy
Edit
python volume_control.py
Show your hand in front of the webcam.

Move your thumb and index finger closer or farther apart.

Watch the system volume change in real-time!

📷 Screenshots


🔍 How It Works
Uses MediaPipe to detect hand landmarks

Measures the Euclidean distance between the tip of the thumb and index finger

Maps that distance to system volume range using NumPy interpolation

Visualizes the control bar and current volume on-screen using OpenCV

📌 Requirements
Python 3.6+

Webcam

Windows OS (for PyCaw-based volume control)

📁 Project Structure
mathematica
Copy
Edit
📦 Volume-Control-using-Hand-Gesture
├── volume_control.py
├── requirements.txt
├── screenshots/
│   ├── hand.png
│   └── volume_control.png
└── README.md
🙋‍♂️ Author
Rohith A P

🏁 Future Enhancements
Add gesture-based mute/unmute

Integrate with Linux/macOS

Add GUI for configuration and settings

🏷️ License
This project is licensed under the MIT License.
