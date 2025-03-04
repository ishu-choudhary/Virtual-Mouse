# Virtual-Mouse
The Virtual Mouse is an AI-based project that enables users to control their computer's cursor using hand gestures. This eliminates the need for a physical mouse by leveraging computer vision techniques. The system uses a webcam to detect hand movements and translates them into cursor actions such as movement, clicking, and scrolling.

Features

Hand Gesture Recognition: Detects hand gestures to perform various mouse operations.

Cursor Control: Move the cursor by moving your hand in front of the camera.

Clicking Actions: Perform left-click and right-click using specific hand gestures.

Scrolling Functionality: Scroll up and down using finger movements.

No Hardware Requirement: Works with a standard webcam without any additional hardware.

Real-time Processing: Ensures smooth and fast response to hand gestures.

Technologies Used

Python

OpenCV (for image processing)

Mediapipe (for hand tracking)

NumPy (for mathematical operations)

PyAutoGUI (for simulating mouse actions)

Installation

Clone the repository:

git clone https://github.com/your-username/virtual-mouse.git
cd virtual-mouse

Install dependencies:

pip install opencv-python mediapipe numpy pyautogui

Run the application:

python virtual_mouse.py

Usage

Place your hand in front of the webcam.

Move your hand to control the cursor.

Use predefined gestures for clicking and scrolling.

Adjust lighting conditions for better accuracy.

Future Enhancements

Adding voice control integration.

Implementing machine learning for improved gesture recognition.

Supporting multi-hand operations.

Contributing

Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

License

This project is licensed under the MIT License.
