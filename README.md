# Haar_Cascade

**From facial recognition to vehicle detection, grasp the essence of Haar Cascade and OpenCV’s role in revolutionizing computer vision. Whether you’re a novice or an expert, this article will equip you with the skills to harness the potential of object detection in your projects.**

## Why Use Haar Cascade Algorithm for Object Detection?
Identifying a custom object in an image is known as object detection. This task can be done using several techniques, but we will use the haar cascade, the simplest method to perform object detection.

## Pre-trained Haar Cascades
The OpenCV library manages a repository containing all popular haar cascades that can be used for:

* Human face detection
* Eye detection
* Nose / Mouth detection
* Vehicle detection
* Spectacles
* Licence Plate

### We can load any haar-cascade XML file using cv2.CascadeClassifier function.
### results It lists coordinates (x, y, w,h) of bounding boxes around the detected object.

## Parameters in detectMultiScale

- scaleFactor – This tells how much the object’s size is reduced in each image.
- minNeighbors – This parameter tells how many neighbours each rectangle candidate should consider.
- minSize — This signifies the minimum possible size of an object to be detected. An object smaller than minSize would be ignored.
    * **Note** : For detection, we must pass a gray_image , scaleFactor, and minNeighbors. Other parameters are optional.

