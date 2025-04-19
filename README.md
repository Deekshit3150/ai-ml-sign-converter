
# 🖐️ Real-Time sign converter using MediaPipe & OpenCV

This project uses MediaPipe and OpenCV to recognize hand gestures in real-time via webcam. It maps each gesture to a corresponding text message using a custom gesture classification function and used for real-time communication for deaf and dumb people



## ✨ Features
Real-time hand gesture detection using a webcam

Classifies gestures such as:

- 🤟I Love You

- 🙁I am Sad

- 🙏Please

- 👏Thank You

- 👎No
 
- 👍Yes

- ✋Stop

- ✌️Peace

- 🤙Call Me

## 🛠️ Installation

Install my-project with npm

```bash
git clone https://github.com/Deekshit3150/ai-ml-sign-converter/blob/main/signConverter.py
cd signConverter
```

Install dependencies

```bash
pip install opencv-python mediapipe
```
## ▶️ Usage
```bash
python gesture_recognition.py

```


## 🧠 How It Works
- MediaPipe Hands is used to track hand landmarks in real-time.

- Custom logic in classify_gesture() compares landmark positions to determine the gesture.

- The gesture is matched with a message from gesture_to_text dictionary.

- OpenCV is used to draw landmarks and display the message on the video feed.


## 🧪 Example Gestures
Gestures

🤟

🙁	

🙏	

👏	

👎	

👍	

✋	

✌️	

🤙	
## 🧩 TODO
- Improve gesture detection accuracy using ML

- Add more gesture definitions

- Build a GUI version

- Export to mobile (Android/iOS) using MediaPipe solutions


## 🙌 Credits
- MediaPipe by Google

- OpenCV

