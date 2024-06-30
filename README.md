# Fire_Smoke_Detection_Using_CNN
Developed Fire and Smoke Detection System using CNN algorithm on Raspberry Pi3

The frames.py, set.py, fr.py files are used in preparing the dataset
The frames.py and fr.py files contain the code to extract frames from a given video.
set.py is used to move a fixed bumber of files chosen at random from one directory to another. This was used to move fixed proportions of total extracted images to form the validation and testing set.

The threadcv.py file contains the code that performs the realtime fire detection and raises an alarm. 
This code is run on the raspberry pi or any other mobile device with the correct environment set. The code will also work perfectly on any desktop computer.
pre-requisite installations (preferrably in a virutal environment) for running the code:
1. Python3
2. OpenCV3
2. Tensorflow
3. keras

Additionaly, A camera would be required to stream live video and a speaker on which the alarm would be raised.
Keep the mp3 file with the siren and the saved model in the same directory as that of threadcv.py

