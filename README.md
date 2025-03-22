# hand_gestures_mouse
HAND GESTURES MOUSE CONTROL :- 
OVERVIEW -
This project demonstrates how to control the mouse cursor using hand gestures in real-time. It leverages computer vision techniques with OpenCV, hand tracking using MediaPipe, and mouse control using PyAutoGUI. The program captures video from a webcam, detects hand landmarks, and maps the position of the index finger to the mouse cursor on the screen. Additionally, it detects a click gesture when the thumb is close to the index finger.

This project is a fun and interactive way to explore the capabilities of computer vision and human-computer interaction. It can be extended for various applications, such as virtual reality, gaming, or accessibility tools.

Features :- 
    Real-Time Hand Tracking: Uses MediaPipe's hand tracking model to detect and track hand landmarks.
    
    
   Mouse Control: Maps the index finger's position to the mouse cursor on the screen.
    
    
   Click Gesture Detection: Detects a click gesture when the thumb is close to the index finger.
    
    
   Cross-Platform: Works on any platform supported by Python, OpenCV, and PyAutoGUI.
    
    
   Customizable: Easily extendable to add more gestures or improve functionality.

Requirements :-

   To run this project, you need the following Python libraries installed:
    
   OpenCV: For video capture and image processing.
    
   MediaPipe: For hand tracking and landmark detection.
    
   PyAutoGUI: For controlling the mouse cursor.
    
    
   You can install the required libraries using pip:
   "pip install opencv-python mediapipe pyautogui"


How It Works :- 

  Hand Detection: The program uses MediaPipe's hand tracking model to detect hands in the webcam feed and extract 21 hand landmarks.
  
  Index Finger Tracking: The position of the index finger tip (landmark 8) is mapped to the screen coordinates.
  
  Mouse Movement: The mouse cursor is moved to the position of the index finger tip.
  
  Click Gesture: A click is triggered when the distance between the thumb tip (landmark 4) and the index finger tip is below a threshold (30 pixels by default).
  
  Visual Feedback: The program displays the webcam feed with hand landmarks drawn on the screen for visual feedback.

Usage :- 

  Clone the repository or download the Python script.
  
  Install the required dependencies (see Requirements).

Run the script:

    python hand_gesture_mouse.py

    
  Position your hand in front of the webcam:
  
  Move your index finger to control the mouse cursor.
  
  Bring your thumb close to your index finger to perform a click.
  
  Press q to quit the program.

Example :-

  Here’s a quick example of how the program works:
  
  Open the program and position your hand in front of the webcam.
  
  Move your index finger to control the mouse cursor.
  
  Bring your thumb close to your index finger to click.
  
  Press q to exit the program.

Limitations :- 

  Lighting Conditions: The program may struggle in low-light or overly bright environments.
  
  Hand Occlusion: Hand tracking may fail if the hand is partially occluded or moves too quickly.
  
  Single Hand: The program currently supports only one hand for simplicity.

Future Improvements :- 

  Multi-Hand Support: Extend the program to support multiple hands for more complex interactions.
  
  Advanced Gestures: Add support for gestures like scrolling, dragging, and right-clicking.
  
  Gesture Training: Use machine learning to train custom gestures for specific actions.
  
  Performance Optimization: Improve performance for low-end devices by optimizing the hand tracking model.

Contributing :- 

  Contributions are welcome! If you have any ideas, suggestions, or bug fixes, feel free to open an issue or submit a pull request.

License :- 
  This project is licensed under the MIT License. 

Acknowledgments :- 
  MediaPipe: For providing an excellent hand tracking model.
  
  OpenCV: For powerful computer vision tools.
  
  PyAutoGUI: For simplifying mouse and keyboard control.

Contact :- 

  For questions or feedback, feel free to reach out:
  
  Email: harshvardhan0867@gmail.com
  
  GitHub: https://github.com/harshvardhan-2003
  
  LinkedIn: https://linkedin.com/in/harshvardhan2907
