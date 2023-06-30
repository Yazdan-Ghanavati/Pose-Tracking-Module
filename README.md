# Pose Tracking Module
This is a computer vision project, which is specifically developed in order to detect and track human Pose.
All the code is written in python and available in the repo for public.

## Libraries
* OpenCV 4.5.3.56
* Mediapipe 0.8.3

## what is Mediapipe pose solution?
In 2019, Google released a deep learning module called Mediapipe which allows users to detect and track various 
body parts in their computer vision projects with a frame rate of 30. This library runs on CPU and does not
require GPU for processing and is currently the fastest method of detection in the market.
This specific module is able to find human pose in a frame and return a list of 33 landmarks which allows user to have
access to the position of each point. These kind of information could be used for healthcare purposes and lead to
design and develop various telemedicine applications.

## Functions
This module is consisted of various functions which are listed below:

* findPose
* findAngle
* findDistance

### findPose
This function will get the input image from webcam and process it in order to find a human pose in the frame.
Although, it can detect everything, it will only print based on the limitations that user set for it. Finally,
it will return a landmark list for each of 33 anatomical landmark including position of every landmark in all
3 directions.  

![image](https://github.com/Yazdan-Ghanavati/Pose-Tracking-Module/assets/137007531/d7495723-a1b3-471d-8997-0386925bf711)


### findAngle
This function is able to find angle between three landmarks and is a great example of practical usage in fitness applications.

![Screenshot (84)](https://github.com/Yazdan-Ghanavati/Pose-Tracking-Module/assets/137007531/c438b661-a5cf-45a9-bc45-f7c9ef4a5609)


### findDistance
This is an extremely important function which can calculate the distance between two landmarks. This function can
be applied to various projects. For instance: workout programs, physiotrapic applications, controlling video games, Exergames.

![Screenshot (80)](https://github.com/Yazdan-Ghanavati/Pose-Tracking-Module/assets/137007531/461898bf-107f-422b-80d9-912c49d42958)



