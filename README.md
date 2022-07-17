# Precision-Spraying-for-Agriculture-mobile-Robot
This project is the HEC funded project, the aim of Precision Agriculture Spraying robot is to develop a robotic solution 
for precisely spraying application for different crops using Machine learning and  Deep learning algorithms.

# DATASET FOR WEED AND PLANT
we used TobSet  for our model training, testing and evaluation.
dataset link: https://github.com/mshahabalam.

# CNN model training

Precision_Spraying_training_CNN.ipynb is used for training our model on TobSet dataset.
# CNN model testing
Precision_Sprayer_testing_CNN.ipynb is used to test our model on different unseen images
some of the results are shown![7](https://user-images.githubusercontent.com/101576446/179397998-645e26f3-7f68-4154-80a6-fc2893182bb9.PNG)
![8](https://user-images.githubusercontent.com/101576446/179398001-d34719cd-91f8-4104-835d-6e4503594cf2.PNG)
![9](https://user-images.githubusercontent.com/101576446/179398003-e25ae09b-012e-4c7a-9037-bdafd44c0e37.PNG)
![10](https://user-images.githubusercontent.com/101576446/179398004-40407a54-d3a8-4441-b454-24a7731e490d.PNG)
![11](https://user-images.githubusercontent.com/101576446/179398005-8ee4ea52-e96f-4c82-b28e-2203da77b72f.PNG)

# Real time spraying and detection of tobacco plants
Real_time_Spraying .ipynb is used to implement our model in real time using webcam, in this file python language
is interfaced with Arduino to activate the nozzle solenoid valve.
In this code we have splitted our webcam video into two halfs, right and left video.
if the tobacco plant is detected in right video so right nozzle should activate and if the tobacco plant 
is detected in left video so left solenoid should activate.

# Image processing to detect tobacco plant
Segmentation and Detection.ipynb file contains the code for detecting only tobacco plant using only image processing techniques.
results are:

![3](https://user-images.githubusercontent.com/101576446/179398258-6a8361c7-7bde-4601-937f-23ee4c4db77d.PNG)
![4](https://user-images.githubusercontent.com/101576446/179398261-b2efb2e5-d3f7-4c89-82d6-66c64028f719.PNG)
![5](https://user-images.githubusercontent.com/101576446/179398263-cbcda528-4c76-48b2-97a2-239d8fc0909a.PNG)
![1](https://user-images.githubusercontent.com/101576446/179398265-0e0b8e38-ea1d-40af-b0ff-5f325a3c9970.PNG)
![2](https://user-images.githubusercontent.com/101576446/179398266-e66e4b56-84a2-417f-9c03-bffe3bbceeef.PNG)
