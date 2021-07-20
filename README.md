# Drone-Surveillance-Contest
Detecting, Tracking and Counting Cars using yolov4 deep sort. 


This repository is made by The AI guy https://github.com/theAIGuysCode/yolov4-deepsort which combines both repository of converting yolo darknet weight file to tensorflow weight file and the DeepSort algorithm.

I worked on this repository and added the cumlative counting of the cars by using an imgainary line then counting each object that passes that line. (from line 226 in object_tracker.py file)

A custom yolov4 model is created, the dataset is created from the given video, the model trained on 120 images and achieved 99.99% map on the training set which is the same as the test set. The model can be found in /data file.
