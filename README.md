#Real-Time Gender Detection with OpenCV and cvlib
This repository contains a Python script for real-time gender detection using OpenCV and the cvlib library. The script utilizes a webcam to capture video frames, detects faces in the frames, and then predicts the gender of each detected face.

#Requirements
Python 3.x
OpenCV
cvlib
NumPy

#Installation
Clone the repository or download the script directly.
Install the required dependencies by running the following command:
Copy code
pip install opencv-python cvlib numpy

#Usage
Connect a webcam to your computer.
Run the script using the following command:
Copy code
python gender_detection.py
A new window will open, showing the real-time video stream from your webcam with gender annotations on each detected face.
Press the 's' key to stop the program.

#How It Works
The script uses OpenCV to access the webcam and capture frames.
Each frame is processed to detect faces using the cv.detect_face() function from the cvlib library.
For each detected face, a rectangle is drawn around it.
The face region is cropped from the frame and passed to the cv.detect_gender() function from cvlib to predict the gender.
The gender label and confidence percentage are displayed on the frame.
The processed frame is shown in a new window in real-time.
Pressing the 's' key terminates the program.



Happy coding!
