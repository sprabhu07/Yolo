# Yolo

## About this project

This project contains a computer vision task that uses a pretrained model like [MobileNet](https://keras.io/api/applications/mobilenet/) for classification of cars and a CNN model like YOLO for object identification. A real time traffic video was used as the input for this project and the model pipeline returns the tagged objects in the video as the output.

## Project structure
The project structure is as follows:

1) clip.mp4

This file contains the video input for the project.

2) output.mp4

This file contains the output video with tagged objects.

3) images

This is a folder that contains different images of 2 classes of cars (Sedan and SUV).

4) Code.ipynb

This .ipynb file contains the complete code for this project. First, a classification model is trained by finetuning a MobileNet model. Then, weights are loaded onto an YOLO model and it is used for object detection. The instructions for loading the weights and using the model can be found [here]((https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/)). 

5) yolo3_one_file_to_detect_them_all.py

This.py file has utility methods for the YOLO model. Courtesy of [Jason Brownlee](https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/).

## Results
The results of the project can be seen closely by looking at the code in the .ipynb file.