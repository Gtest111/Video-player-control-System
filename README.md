Created a project that wroks on hand recognition using python different moudles.   
Model recognize the different hand guestures and then send commands to the video player based upon the partiular guesture.   

Run the following command to install cv2:   
bash : pip install opencv-python    

If you're using Python 3 and pip is associated with Python 3, you might need to use pip3 instead:     
bash : pip3 install opencv-python    


Run the following command to install mediapipe:    
bash : pip install mediapipe    

If you're using Python 3 and pip is associated with Python 3, you might need to use pip3 instead:    
bash : pip3 install mediapipe    


To install the pyautogui library, you can use pip. Here's how you can do it:     
bash : pip install pyautogui     
 
If you're using Python 3 and pip is associated with Python 3, you might need to use pip3 instead:    
bash : pip3 install pyautogui       


To install the time library in Python, you don't need to install anything separately. It is a standard Python library and comes built-in with Python, so you can use it directly in your code without any additional installation steps.      

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Description: Developed a Python-based application that uses hand gesture recognition to control the video player on YouTube. The system allows users to play, pause, fast-forward, rewind, and adjust the volume of YouTube videos through specific hand gestures.

Technologies Used
1. Python
Description: The core programming language used to develop the application, leveraging its robust libraries for computer vision and machine learning.

2. OpenCV
Description: A powerful library used for real-time computer vision tasks, including capturing and processing video frames to detect hand gestures.

3. MediaPipe
Description: A framework developed by Google that provides machine learning solutions for recognizing and tracking hand landmarks, facilitating gesture recognition.

4. PyAutoGUI
Description: A library used to automate mouse and keyboard interactions, enabling the application to control the YouTube video player based on recognized gestures.

5. Time
Description: A Python module used for timing-related operations, such as measuring the duration of gestures.

Functionalities

1. Hand Gesture Recognition
Technical Term: Computer Vision and Machine Learning
Description: The system captures video frames using OpenCV and uses MediaPipe to detect and track hand landmarks. Specific hand gestures are recognized and mapped to video player controls.

2. Video Player Control
Technical Term: Automation
Description: PyAutoGUI is used to simulate mouse clicks and keyboard presses to control the YouTube video player based on the recognized hand gestures.

3. Real-Time Processing
Technical Term: Real-Time Computer Vision
Description: The application processes video frames in real-time to ensure that hand gestures are recognized and acted upon immediately.

4. Gesture Mapping
Technical Term: Gesture-Action Mapping
Description: Specific hand gestures are mapped to video player controls such as play, pause, fast-forward, rewind, and volume adjustment. For example, an open hand might pause the video, while a closed fist might play it.

Workflow
Video Capture: The application captures video frames from the webcam using OpenCV.
Gesture Detection: MediaPipe processes the frames to detect and track hand landmarks.
Gesture Recognition: The detected hand landmarks are analyzed to recognize specific gestures.
Control Mapping: Recognized gestures are mapped to corresponding YouTube video player actions.
Player Control: PyAutoGUI automates mouse and keyboard actions to control the YouTube player based on the recognized gestures.

Summary
This project demonstrates the integration of computer vision, machine learning, and automation to create an innovative user interface for controlling YouTube videos through hand gestures. It leverages Python's powerful libraries to provide a seamless and interactive experience.
