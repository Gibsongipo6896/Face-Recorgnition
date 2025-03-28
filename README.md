Face Match with DeepFace

This project captures webcam video and matches the face in the video with a reference image using DeepFace for facial recognition. It displays "MATCH!" or "NO MATCH!" on the screen based on the result.

Requirements:
- Python 3.x
- OpenCV
- DeepFace

Install dependencies:
pip install opencv-python deepface

Usage:
1. Place your reference image in the same directory as the script (reference.jpg).
2. Run the script:
   python face_match.py
3. The webcam feed will open, showing either "MATCH!" (green) or "NO MATCH!" (red) depending on face recognition.
4. Press 'q' to quit.

Code Overview:
- Face Verification: The check_face() function verifies the face in each frame with the reference image.
- Multithreading: Face checks run in separate threads for smooth video capture.
- Real-time Results: The result ("MATCH!" or "NO MATCH!") is displayed on the video feed.

Author:
- Gibson
