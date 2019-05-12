# Sign Language Prediction
Sign language prediction using CNN
There is a need of a method or an application that can recognize sign language gestures so that the communication is possible even if someone does not understand sign language. With this work, we intend to take a basic step in bridging this communication gap using Sign Language Recognition.

# A quick sneak-peak into what was done
1.Firstly, we've created 44 gesture samples using OpenCV, in which,for each gesture we've captured 1200 images each of 50x50 pixels.All theses images were in grayscale which is stored in the gestures/ folder. The pictures were flipped using flip_images.py. This script flips every image along the vertical axis. Hence each gesture has 2400 images.
2. Created a CNN using keras and TensorFlow. All the gestures that are present in this repo are basic, if you want to add more gestures, you can create your own gestures.
3. Then used the model which was trained using Keras on a video stream.

# Requirements
Python 3.x

Tensorflow 1.5

Keras

OpenCV 3.4

h5py

pyttsx3

Now,let's dive deep into steps done. 



