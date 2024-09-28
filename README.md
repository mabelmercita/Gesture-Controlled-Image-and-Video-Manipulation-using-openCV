Gesture-Controlled Image and Video Manipulation using Computer Vision

📋 Project Overview
This project uses OpenCV and HandTrackingModule to enable users to manipulate images and control videos through hand gestures detected via a webcam. It supports zooming in/out on images and controlling video playback using hand gestures such as finger movements.

⚙️ Features
Detects hand gestures using a webcam.
Zoom in/out on an image by moving hands closer or farther apart.
Control video playback:
Fast-forward: Raise index finger.
Rewind: Raise index and middle fingers.
Pause/Play: Raise all fingers.
Screenshot: Raise index, middle, and ring fingers.

🛠️ Technologies Used
Python
OpenCV (for video capture and image processing)
cvzone HandTrackingModule (for hand gesture detection)
PyAutoGUI (for video control automation)

✨ How It Works
Hand Detection: The webcam detects hand gestures using HandDetector from cvzone.HandTrackingModule.
Gesture Control:
Two Hands Gesture: Control the zoom of an image based on the distance between both hands.
Single Hand Gesture: Control video playback using different finger combinations.
Image Manipulation: Resizes and centers the image based on hand gestures.

🙌 Acknowledgements
Inspiration and guidance from various computer vision tutorials.
