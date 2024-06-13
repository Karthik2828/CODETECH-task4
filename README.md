Name: B Teja Karthik
Company: CODETECH IT SOLUTIONS
ID: CT12DS513
Domain: Artificial Intelligence
Duration: June to August 2024
Mentor: Muzammil

Overview of the Project

Project: Computer Vision Task
Project output: <img width="1710" alt="Screenshot 2024-06-13 at 7 11 01 PM" src="https://github.com/Karthik2828/CODETECH-task4/assets/116016314/7afdf768-cdfd-451b-ad2c-3caa094f9cc4">


Objective

The objective of this project is to develop an efficient computer vision algorithm to accurately detect and track fingers in real-time, aiming to enhance human-computer interaction and gesture recognition systems.

Key Activities

1.Video Processing:
  -Reading each frame from the video.
  -Converting the frame to RGB format for compatibility with the hand detection model.
2.Hand Detection:
  -Processing each frame to detect hand landmarks using the hand detection model.
  -Extracting landmark information for each detected hand.
3.Drawing Landmarks:
  -Drawing the landmarks on the frame using OpenCV's drawing functions.
4.Finger Tracking:
  -Extracting finger coordinates and thumb coordinate.
  -Calculating the number of raised fingers based on their relative positions.
5.Displaying Results:
  -Drawing circles on detected finger points.
  -Displaying the count of raised fingers on the frame.
6.User Interaction:
  -Continuously displaying the processed frames and updating the display.
  -Exiting the loop if the user presses any key.


Technologies Used


1.OpenCV (cv2): 
OpenCV (Open Source Computer Vision Library) is a popular open-source computer vision and machine learning software library. In this code, OpenCV is used for video capture, image processing, drawing, and displaying the processed frames.

2.MediaPipe: 
MediaPipe is an open-source framework for building cross-platform, scalable, and high- performing pipelines for inference in various perception tasks. Here, MediaPipe is specifically used for hand tracking and landmark detection.

3.Python:
Python is the programming language used to write the code. Python is widely used in the field of computer vision due to its simplicity, extensive libraries, and readability.

4.Hand Tracking and Finger Detection Algorithms: 
The code implements algorithms for hand tracking and finger detection. These algorithms are based on machine learning models and computer vision techniques provided by the MediaPipe library.
