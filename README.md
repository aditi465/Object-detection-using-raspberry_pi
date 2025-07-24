# Real-Time Object Detection on Raspberry Pi 3B+ using YOLOv5n

This project implements real-time object detection using the *YOLOv5n* model and an *OmniVision camera* on a *Raspberry Pi 3B+.
The object detection pipeline is powered by OpenCV  module, allowing you to perform inference without installing large 
frameworks like PyTorch . It is lightweight, fast, and optimized for edge computing on low-power hardware.

##  Algorithm Overview

*YOLO (You Only Look Once)* is a fast and efficient object detection algorithm that identifies objects in an image in a single
pass through the neural network. This project uses *YOLOv5n* (the nano variant of YOLOv5), which is specifically optimized for 
edge devices with limited compute power, like the Raspberry Pi 3B+.
Instead of running the model with PyTorch, the project uses the *ONNX version of YOLOv5n, loaded and executed through **OpenCV’s DNN module*.
This reduces the computational load and eliminates the need for large AI frameworks, enabling real-time inference on the Raspberry Pi.

##  Hardware Used

This project was built and tested using the following hardware components:

- *Raspberry Pi 3B+*  
  A compact and affordable single-board computer capable of basic AI inference tasks.

- *OmniVision Camera Module*  
  A CSI or USB camera used to capture real-time video frames for object detection.

- *MicroSD Card (16GB or larger)*  
  Required to run Raspberry Pi OS and store model files.

- *HDMI Monitor / VNC or SSH Access*  
  For displaying the detection results or managing the Pi remotely.

  
##Reference

*This project was inspired and partially guided by the tutorial from Core Electronics:

- [Getting Started with YOLO Object and Animal Recognition on the Raspberry Pi](https://core-electronics.com.au/guides/raspberry-pi/getting-started-with-yolo-object-and-animal-recognition-on-the-raspberry-pi/)


  
