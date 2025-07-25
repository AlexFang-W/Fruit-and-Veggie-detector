# Fruit & Vegetable Classifier
An AI model designed to identify different fruits and vegetables from submitted images. The model uses deep learning and computer vision techniques to classify various produce types with high accuracy. It is intended for applications such as grocery automation, dietary tracking, educational tools, and AI-powered kitchen assistants.

(Sample: https://drive.google.com/file/d/1ru1cwMjjzkJRY-QYpkvISBW1F0Bi4U8T/view?usp=sharing )

(Sample: https://drive.google.com/file/d/1Lc1rxkkKFxuym5QS-EjYAGMBfSOo4skj/view?usp=sharing )
## The Algorithm
This algorithm uses the NVIDIA Jetson Nano, using the jetson-inference framework with a pre-trained model through the Open Neural Network Exchange (ONNX), a classification model.

Camera → Preprocessing → CNN Model → Class Label + Confidence → Display

Steps Taken by the Program:
- load an image - it does support live detection
- classify the fruit or veggie
- matching the label to the object displayed in the image along with its confidence on the image.
- It would then overlay the confidence and the matching label onto the image
you can then save the new image with the classification.

## Running this Project
1. Clone this repository

(Video: https://drive.google.com/file/d/14t0fi99A6TtwYR_JhPFuL2vQj72hEfP3/view?usp=sharing )
