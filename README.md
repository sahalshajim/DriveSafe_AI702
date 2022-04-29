# 🚗DriveSafe🚗

---

## Introduction

***DriveSafe*** is a driver assistance system utilizing efficient mobile computer vision models in order to deliver enhanced safety to drivers. Features of this sytem include traffic light detection, stop sign detection, distance monitoring based on vheicle speed and pedestrian collision warning. Some of the features can be seen below.




<p align="center">
  <img width="250"  src="./images/distance.gif">
  <img width="250"  src="./images/traffic.gif">
  <img width="250"  src="./images/pedestrian.gif">
</p>

## Object Detector
MS COCO Pre-trained models were used to fine-tune on the BDD100k dataset. The models were trained using `TensorFlow Object Detection API`. Detailed instructions for training the model and the demo inference script is given in the `/Object_Detection` folder.

## Dataset

The fine-tuning stage requires correctly formatted `tfrecord` files. In order to create this from raw BDD100k images and labels please follow the instructions from `/Dataset` and copy the generated dataset to `/Object_Detection/trainingdemo/annotations/`

## Mobile application

## References
