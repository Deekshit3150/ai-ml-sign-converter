🖐️ Real-Time Hand Gesture Recognition using MediaPipe & OpenCV
This project uses MediaPipe and OpenCV to recognize hand gestures in real-time via webcam. It maps each gesture to a corresponding text message using a custom gesture classification function.

📹 Demo
https://user-images.githubusercontent.com/yourusername/demo.mp4 (Optional demo video)

✨ Features
Real-time hand gesture detection using a webcam

Classifies gestures such as:

I Love You

I am Sad

Please

Thank You

No

Yes

Stop

Peace

Call Me

Visual feedback with landmarks and gesture text on the video

🛠️ Installation
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
2. Create a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install opencv-python mediapipe
▶️ Usage
Run the script:

bash
Copy
Edit
python gesture_recognition.py
A window will open showing your webcam feed with real-time hand tracking and gesture classification. Press q to quit.

📁 File Structure
bash
Copy
Edit
├── gesture_recognition.py   # Main script
├── README.md                # Project documentation
🧠 How It Works
MediaPipe Hands is used to track hand landmarks in real-time.

Custom logic in classify_gesture() compares landmark positions to determine the gesture.

The gesture is matched with a message from gesture_to_text dictionary.

OpenCV is used to draw landmarks and display the message on the video feed.

🧪 Example Gestures
Gesture	Meaning
🤟	I Love You
🙁	I am Sad
🙏	Please
👏	Thank You
👎	No
👍	Yes
✋	Stop
✌️	Peace
🤙	Call Me
Note: Gesture classification is rule-based and may need tuning based on camera angle and hand positioning.

🧩 TODO
Improve gesture detection accuracy using ML

Add more gesture definitions

Build a GUI version

Export to mobile (Android/iOS) using MediaPipe solutions

🙌 Credits
MediaPipe by Google

OpenCV

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
