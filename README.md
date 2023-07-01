# Hand-Gesture-Recognition-System-Using-Holistic-Mediapipe


The aim of this project was to build a viable Recurrent neural
Network(RNN) that distinguishes gestures that are trained in real-time by a picture of a signed hand.
Technology: Holistic Mediapipe, Sign language recognition [SLR], LSTM, Computer Vision, Deep Learning, RNN.

Train our own dataset
   
To run the code, you need to have the necessary dependencies installed, including OpenCV, numpy, media pipe, and TensorFlow. Make sure you have these libraries installed before running the code.

Here's a step-by-step guide on how to run the code:

Install the required dependencies: OpenCV, numpy, media pipe, and TensorFlow.
Save the code in a Python script (e.g., gesture_recognition.py).
Open a terminal or command prompt and navigate to the directory where the script is saved.
Run the script by executing the command: python gesture_recognition.py.   
The script will start capturing video from your webcam and perform real-time gesture recognition. It will display the recognized gesture as text on the screen and update the text as you perform different gestures. The recognized gestures are based on the trained LSTM model's predictions.

Please note that this code assumes you have already trained an LSTM model for gesture recognition and saved it as 'action2.h5'. If you haven't trained the model yet, you'll need to train it using a dataset of gesture videos and save the trained model before running this script.
