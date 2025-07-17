Handwritten Digit Recognition
Welcome to the Handwritten Digit Recognition v0.1 project, inspired by NeuralNine tutorials. This project trains a neural network model to recognise handwritten digits using the MNIST dataset with TensorFlow and Keras.

📝 Project Description
This project builds and trains a neural network to classify handwritten digits (0–9) from the MNIST dataset with high accuracy. It also includes a prediction script to classify custom digit images saved locally.

🚀 Features
Loads and preprocesses MNIST data

Builds a Sequential neural network with Dense layers

Trains the model with ReLU and softmax activations

Saves the trained model for later use

Predicts external digit images saved in a digits/ folder

💻 Technologies Used
Python

TensorFlow / Keras

NumPy

OpenCV

Matplotlib

⚙️ Setup Instructions

Clone this repository
git clone https://github.com/Gaurravvvv/handwritten-digit-recognition.git
cd handwritten-digit-recognition

Install dependencies
pip install tensorflow numpy opencv-python matplotlib

Run the notebook
jupyter notebook Try_1.ipynb

Add custom images

Save your digit images in the digits/ folder as digit1.png, digit2.png, etc.

Images should be 28x28 pixels, single-channel (greyscale) for accurate prediction.

📂 Files
Try_1.ipynb – Main Jupyter notebook with model training and prediction code

handwritten_digits.keras – Saved model file (generated after training)

✍️ Author
Gaurravvvv 
