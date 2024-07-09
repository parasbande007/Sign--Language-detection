# Sign Language Detection using Action Recognition
This project focuses on detecting sign language gestures using action recognition techniques implemented with Python. The model is based on LSTM (Long Short-Term Memory) networks, leveraging the capabilities of Mediapipe for keypoint detection and TensorFlow for deep learning.

## Installation
Ensure you have Python installed. Required libraries include numpy, tensorflow, opencv-python, mediapipe, scikit-learn, and matplotlib.

## Dataset Preparation
- **Keypoint Extraction:** Use Mediapipe to extract keypoints for the face, pose, and hands.
- **Data Collection:** Collect a dataset of sign language gestures and organize the data into sequences of frames.

## Model Training
- **Model Architecture:** A Sequential model consisting of three LSTM layers followed by dense layers is used.
- **Compilation:** The model is compiled using the Adam optimizer and categorical cross-entropy loss function.
- **Training:** The model is trained for 1000 epochs. TensorBoard is used for monitoring the training process.

## Model Parameters:
- **Neurons:** Layers have 64 and 128 neurons to balance complexity and computational efficiency.
- **Activation Functions:** ReLU activation functions are used to introduce non-linearity, allowing the model to learn complex patterns.

## Results
The model's performance can be evaluated using metrics like accuracy and confusion matrices. Visualization tools help in understanding and interpreting the model's predictions and overall performance.
