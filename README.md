# Hand Gesture Recognition with TensorFlow and OpenCV

This project showcases a real-time hand gesture recognition system implemented using TensorFlow and OpenCV. The goal of the system is to detect hand gestures from a video feed and perform corresponding actions based on the recognized gestures.

## Features
- Real-time hand gesture recognition using a webcam or camera feed.
- Detects hand gestures such as moving left, moving straight, moving right, and going forward.
- Uses a pre-trained TensorFlow model for hand detection and classification.
- Provides visual feedback by overlaying detected gestures on the video feed.
- Adjustable parameters for threshold, width, height, and alpha.
- Utilizes multiprocessing for efficient performance and multi-threaded execution.

## How It Works
1. The system captures video frames from a camera feed.
2. Each frame is preprocessed by flipping, converting color spaces, and resizing.
3. Hand detection is performed using a pre-trained TensorFlow model.
4. Detected hand gestures are classified into categories based on their positions.
5. Corresponding actions are triggered based on the recognized gestures.
6. Visual feedback is provided by drawing circles and text on the video feed.
7. An overlay is added to highlight specific regions of interest.
8. The processed video feed is displayed in real-time.

## Prerequisites
- TensorFlow
- OpenCV
- Python 3.x

## Usage
1. Install the required dependencies mentioned in the prerequisites.
2. Clone this repository to your local machine.
3. Run the script `main.py` using Python.
4. Ensure that a camera is connected and accessible.
5. Perform hand gestures in front of the camera to see the system in action.
6. Press 'q' to quit the application.

## Contributions
Contributions to this project are welcome! If you find any bugs or have ideas for enhancements, please submit an issue or a pull request. Let's collaborate to improve this hand gesture recognition system together.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for personal or commercial purposes.

## Acknowledgments
Special thanks to the authors of the pre-trained TensorFlow model used in this project and the open-source community for their contributions to TensorFlow and OpenCV.

## Disclaimer
This hand gesture recognition system is intended for educational and experimental purposes only. Use with caution and responsibility.
