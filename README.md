# YOLO_Object_detection
This repository contains a pre-trained object detection model based on YOLO, which has been trained on the VisDrone dataset. The model is capable of classifying both images and videos and can detect several classes, including 'pedestrian', 'people', 'bicycle', 'car', 'van', 'truck', 'tricycle', 'awning-tricycle', 'bus', and 'motor'.
The following diagram illustrates the output of the algorithm on various images:

![output_yolo_vis_drone](https://github.com/KosarBehnia/YOLO_Object_detection/assets/27929518/97fdd018-62e9-4309-b088-609be65176cd)
![output_yolo_vis_drone_2](https://github.com/KosarBehnia/YOLO_Object_detection/assets/27929518/efaa23f0-fc69-4fd4-bb7d-cc7765ab5e2f)


When outliers are ignored in the training dataset and the input images are adjusted to have a brightness of 0.89 and contrast of 0.79, the following training and validation metrics are obtained:

![train_graphs](https://github.com/KosarBehnia/YOLO_Object_detection/assets/27929518/0a7dbead-2778-4f82-9780-0e86da1f6476)
![validation_graphs](https://github.com/KosarBehnia/YOLO_Object_detection/assets/27929518/22e35970-3f45-434f-b956-9375b4b775b8)
