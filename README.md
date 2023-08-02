# Facial Recognition with Deep Learning in Keras Using CNN

Facial recognition is a biometric alternative that measures unique characteristics of a humanface. Applications available today include flight check in, tagging friends and family members in photos, and “tailored” advertising.<br>

### Problem Objective:
Use a deep convolutional neural network to perform facial recognition using Keras.<br>

### Dataset Details:
ORL face database composed of 400 images of size 112 x 92. There are 40 people, 10 imagesper person. The images were taken at different times, lighting and facial expressions. The facesare in an upright position in frontal view, with a slight left-right rotation.<br>


### Steps to be followed:
1. Input the required libraries
2. Load the dataset. Normalize every image.
3. Split the dataset
4. Transform the images to equal sizes to feed in CNN5. Build a CNN model that has 3 main layers:
  i. Convolutional Layer
  ii. Pooling Layer
  iii. Fully Connected Layer
6. Train the model
7. Plot the result
8. Iterate the model until the accuracy is above 90%<br>


### Setup and Installation:
```bash
pip install --upgrade pip
pip install -r requirements.txt
pip list
```
