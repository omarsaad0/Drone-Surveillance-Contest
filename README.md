# Drone-Surveillance-Contest
Detecting, Tracking and Counting Cars using yolov4 deep sort. 


This repository is made by The AI guy https://github.com/theAIGuysCode/yolov4-deepsort which combines both repository of converting yolo darknet weight file to tensorflow weight file and the DeepSort algorithm.

I worked on this repository and added the cumlative counting of the cars by using an imgainary line then counting each object that passes that line. (from line 226 in object_tracker.py file)

A custom yolov4 model is created, the dataset is created from the given video, the model trained on 120 images and achieved 99.99% map on the training set which is the same as the test set. The link to the model (Drive) https://drive.google.com/file/d/14P7HjjaSH7GoGmlH8JWSFpH6hrqeaiMw/view?usp=sharing

The inside REAMME.md file explains all the steps from installing the required libraries in an environment in conda or using pip to run detection and tracking on videos or webcam. 

https://www.youtube.com/watch?v=l81wMCmdvCk

https://user-images.githubusercontent.com/76915795/128122809-c0e1cbfc-2139-4fba-8e33-3831bf8c5ff7.mp4

