Detecting-a-Drivers-Drowsiness-and-Mobile-phone-distraction-using-Computer-Vision

The aim of the project is to use Computer Vision for detection of a driver's drowsiness or mobile phone distraction during driving.

We use facial landmark detection (pretrained model) for extracting the features of the eyes from the face.

Then we calculate the Eye Aspect Ratio (EAR) from the extracted features and if the ratio is below a certain threshold for a certain number of consecutive frames, we declare that we have detected drowsiness or distraction and hence play an alarm.
