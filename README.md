Emotion Detection using Deep Learning
Overview: This project aims to detect emotions in real-time using a deep learning model and a webcam. It utilizes a Convolutional Neural Network (CNN) trained on the FER-2013 dataset for emotion classification. The project also employs the OpenCV library to detect faces in live video feed from the webcam, and then the detected face is processed through the trained model to predict the emotion.

Table of Contents
-> [Prerequisites](#prerequisites)
-> [Getting Started](#getting-started)
-> [Usage](#usage)
-> [Model Architecture](#model-architecture)
-> [Results](#results)
-> [License](#license)
-> [Acknowledgments](#acknowledgments)

## Prerequisites
Before running this project, make sure you have the following installed:

- Python (version X.X)
- Libraries (add a list of libraries and their versions)
- Webcam

## Getting Started
1. Clone this repository to your local machine.

2. Install the required Python libraries using pip.


3. Download the pre-trained emotion detection model weights and place them in the project directory. You can find the model [here](https://link-to-model-weights).

## Usage
1. Run the main application by executing the following command.
   ```
   python emotion_detection.py
   ```

2. The webcam will activate, and emotions will be detected in real-time on faces within the camera's view.

3. To exit the application, press 'q'.

## Model Architecture
The deep learning model used for emotion detection is a custom CNN with the following architecture:

- Input layer (48x48 grayscale image)
- Three Separable Convolutional Blocks
- Global Max Pooling Layer
- Fully connected layers
- Softmax output layer
