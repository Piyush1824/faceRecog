Facial Recognition Attendance System

A Python-based Facial Recognition Attendance System that uses a webcam to identify known faces in real time and automatically records attendance in a CSV file with date and time.
This project leverages computer vision and face recognition techniques to provide a simple and efficient attendance solution.

Features :

-Real-time face detection using webcam.

-Face recognition based on pre-stored images.

-Automatic attendance logging in CSV format.

-Date-wise attendance records.

-Displays recognized person as Present on screen.

-Easy to extend for multiple users.

Tech Stack :

-Python.

-OpenCV : for video capture and image processing.

-face_recognition : for face detection and encoding.

-NumPy : for numerical operations.

-CSV module : for attendance storage.

How It Works :

[ Prerequisite Create faces folder in same directory and store facial images with individual names in it ]

-The system loads images of known individuals from the faces folder.

-Each image is converted into a facial encoding.

-The webcam captures live video frames.

-Faces in the live video are detected and compared with known face encodings.

-If a match is found:
   
   1.The person’s name is displayed on the screen.

   2.Attendance is recorded in a CSV file with date and time.

-Attendance is recorded only once per person per session.

Required Libraries :

Run the following commands:
   
    pip install cmake
    
    pip install face_recognition
    
    pip install numpy
    
    pip install opencv-python

Author,

Piyush Shinde    
