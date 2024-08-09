# Virtual Mouse and Volume Controller Using Hand Gestures

This project allows you to control your computer's mouse and adjust the volume using hand gestures detected by a webcam. By leveraging OpenCV for image processing, MediaPipe for hand tracking, and PyAutoGUI for simulating mouse movements and volume control, this application provides a more intuitive way to interact with your computer.

## Features

- **Virtual Mouse Control:**
  - **Move Cursor:** Control the position of the mouse cursor using the movement of your index finger.
  - **Click Action:** Perform right-clicks using specific gestures:
    - **Right Click:** Index and middle fingers make contact.

- **Volume Control:**
  - **Increase Volume:** Adjust the system volume up by making a fist with your hand.
  - **Decrease Volume:** Adjust the system volume down by opening your hand.

- **Gesture Recognition:**
  - Detects and interprets various hand gestures to control both the mouse and volume.

## Technologies Used

- **OpenCV:** For video capture and image processing.
- **MediaPipe:** For hand tracking and landmark detection.
- **PyAutoGUI:** For simulating mouse movements and volume control.
- **Python 3.7:** Programming language used for implementation.
