🎯 Eye-Controlled Mouse
Navigate Your Computer with Just Your Eyes

This innovative project leverages computer vision and facial landmark detection to enable hands-free mouse control. By tracking eye movements and detecting blinks, users can move the cursor and perform click actions—making this a powerful tool for accessibility, productivity, and creative human-computer interaction.

🚀 Features
✅ Real-Time Eye Tracking – Utilizes MediaPipe for precise and efficient eye movement tracking

✅ Blink Detection for Clicking – Enables left-click actions using intentional blinks

✅ Smooth and Responsive Cursor Movement – Achieved through OpenCV and PyAutoGUI integration

✅ Accessible and Intuitive – Designed for ease of use with minimal setup

✅ Lightweight & High-Performance – Low latency and optimized for real-time applications

🛠 Tech Stack
Python 🐍 – Core programming language

OpenCV 👁 – Image processing and frame capture

MediaPipe 🎯 – Facial landmark detection and eye tracking

PyAutoGUI 🖱 – Programmatic control of mouse cursor and clicks 

Setup Instructions
Follow the steps below to get the Eye-Controlled Mouse running on your system:

🔧 Prerequisites
Make sure you have the following installed:

Python 3.7+

Webcam (for eye tracking)

pip (Python package installer)

📦 Step 1: Clone the Repository
git clone https://github.com/your-username/eye-controlled-mouse.git
cd eye-controlled-mouse

🐍 Step 2: Create and Activate a Virtual Environment (Optional but Recommended)
python -m venv venv

# Activate:
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

📥 Step 3: Install Dependencies

pip install -r requirements.txt
Or manually install:

pip install opencv-python mediapipe pyautogui

▶️ Step 4: Run the Application

python eye_mouse.py
📝 Make sure your webcam is connected and accessible.

🖥 System Requirements
OS: Windows, macOS, or Linux

Webcam: Built-in or USB

Python: 3.7 or higher

RAM: 4GB or more (recommended)


