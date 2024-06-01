# HAND GESTURE VOLUME CONTROL

This project demonstrates how to control the volume of your computer using hand gestures captured through a webcam. The implementation uses OpenCV for image processing, a custom HandTrackingModule for detecting and tracking hand positions, and the Pycaw library for volume control.

## Requirements

* Python 3.x
* Opencv
* Numpy
* Comtypes
* HandTrackingModule {Already uploaded on GitHub}

## Installation
Clone the repository:
```sh
git clone https://github.com/shrey-mishra/hand-gesture-volume-control.git
cd hand-gesture-volume-control
```

Before running the project, make sure you have all the required libraries installed. You can install them using pip:

```bash
pip install requirements.txt
```

## Usage

1. Clone the repository or download the code.
2. Make sure your webcam is connected and working.
3. Run the script:

```sh 
python hand_volume_control.py
```

## Project Structure 
`hand_volume_control.py`: Main script to run the hand gesture volume control.

## How It Works

1. Initialize Webcam: The script starts by initializing the webcam feed.
2. Hand Detection: The `HandTrackingModule` is used to detect hands and track the position of key landmarks on the hand.
3. Volume Control: The distance between the thumb and index finger is calculated. This distance is mapped to the system volume range using the Pycaw library.
4. Visual Feedback: Circles and lines are drawn on the image to provide visual feedback of the hand positions and the detected gestures.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgment

* Murtaza's Workshop - Robotics and AI for the `HandTrackingModule`.
* Andre Miras for the Pycaw library.


For any queries or issues, please feel free to open an issue in the repository.
