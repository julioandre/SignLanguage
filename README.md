# SignLanguage

This repo contains the code for a Sign Language Classifier. It uses computer vision and python to build an American Sign Language Translator 
and using the webcam to record live video as input

# Dependencies and Libraries
* OpenCV
* NumPy
* PyTorch

# Folder Structure/Code Explanation 
* Data Folder: This contains all the data sets we used in training and testing our models
* SignLanguage: This folder contains the python environment files to help us create a virtual environment to run the code
* step_2_dataset.py: This file contains code for preparing the data set for training 
* step_3_train.py: This file contains the code for building and training the sign language classifier
* step_4_evaluate.py: This code evaluates the classifier and its accuarcy and translating the signs
* step_5_camera.py: This file contains code to connect a webcam as input for the application

# Running the application

To run this application we first need to activate the virtual python environment by running the command $source signlanguage/bin/activate
Finally to run the application type this command into your terminal $python step_3_train.py   



