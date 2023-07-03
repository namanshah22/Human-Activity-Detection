# Human Activity Detection

This project utilizes computer vision techniques to detect human activity in videos. It uses a pre-trained human activity recognition model to classify different activities performed by humans in real-time.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- imutils

## Installation

1. Clone the repository or download the project files.

2. Install the required Python dependencies:
 pip install opencv-python numpy imutils

3. Download the pre-trained human activity recognition model and class labels file.

## Usage
python human_activity_reco_deque.py --model resnet-34_kinetics.onnx --classes action_recognition_kinetics.txt --input example_activities.mp4


## Notes

- The human activity recognition model file and class labels file should be provided in the appropriate formats compatible with the script.

- Press 'q' to exit the application.

## Acknowledgments

- Pre-trained model - resnet-34_kinetics.onnx
- Dataset used for training - action_recognition_kinetics.txt




